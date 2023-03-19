!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
The installed Theano(-PyMC) version (1.0.5) does not match the PyMC3 requirements.
It was imported from ['C:\\Users\\Mfund\\anaconda3\\lib\\site-packages\\theano']
For PyMC3 to work, a compatible Theano-PyMC backend version must be installed.
See https://github.com/pymc-devs/pymc3/wiki for installation instructions.
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
Unexpected exception formatting exception. Falling back to standard exception
Traceback (most recent call last):
  File "C:\Users\Mfund\anaconda3\lib\site-packages\IPython\core\interactiveshell.py", line 3460, in run_code
    exec(code_obj, self.user_global_ns, self.user_ns)
  File "C:\Users\Mfund\AppData\Local\Temp\ipykernel_9080\948132345.py", line 4, in <module>
    import pymc3 as pm
  File "C:\Users\Mfund\anaconda3\lib\site-packages\pymc3\__init__.py", line 112, in <module>
    __set_compiler_flags()
  File "C:\Users\Mfund\anaconda3\lib\site-packages\pymc3\__init__.py", line 83, in __set_compiler_flags
    current = theano.config.gcc__cxxflags
AttributeError: 'TheanoConfigParser' object has no attribute 'gcc__cxxflags'

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "C:\Users\Mfund\anaconda3\lib\site-packages\IPython\core\interactiveshell.py", line 2057, in showtraceback
    stb = self.InteractiveTB.structured_traceback(
  File "C:\Users\Mfund\anaconda3\lib\site-packages\IPython\core\ultratb.py", line 1118, in structured_traceback
    return FormattedTB.structured_traceback(
  File "C:\Users\Mfund\anaconda3\lib\site-packages\IPython\core\ultratb.py", line 1012, in structured_traceback
    return VerboseTB.structured_traceback(
  File "C:\Users\Mfund\anaconda3\lib\site-packages\IPython\core\ultratb.py", line 865, in structured_traceback
    formatted_exception = self.format_exception_as_a_whole(etype, evalue, etb, number_of_lines_of_context,
  File "C:\Users\Mfund\anaconda3\lib\site-packages\IPython\core\ultratb.py", line 818, in format_exception_as_a_whole
    frames.append(self.format_record(r))
  File "C:\Users\Mfund\anaconda3\lib\site-packages\IPython\core\ultratb.py", line 736, in format_record
    result += ''.join(_format_traceback_lines(frame_info.lines, Colors, self.has_colors, lvals))
  File "C:\Users\Mfund\anaconda3\lib\site-packages\stack_data\utils.py", line 145, in cached_property_wrapper
    value = obj.__dict__[self.func.__name__] = self.func(obj)
  File "C:\Users\Mfund\anaconda3\lib\site-packages\stack_data\core.py", line 698, in lines
    pieces = self.included_pieces
  File "C:\Users\Mfund\anaconda3\lib\site-packages\stack_data\utils.py", line 145, in cached_property_wrapper
    value = obj.__dict__[self.func.__name__] = self.func(obj)
  File "C:\Users\Mfund\anaconda3\lib\site-packages\stack_data\core.py", line 649, in included_pieces
    pos = scope_pieces.index(self.executing_piece)
  File "C:\Users\Mfund\anaconda3\lib\site-packages\stack_data\utils.py", line 145, in cached_property_wrapper
    value = obj.__dict__[self.func.__name__] = self.func(obj)
  File "C:\Users\Mfund\anaconda3\lib\site-packages\stack_data\core.py", line 628, in executing_piece
    return only(
  File "C:\Users\Mfund\anaconda3\lib\site-packages\executing\executing.py", line 164, in only
    raise NotOneValueFound('Expected one value, found 0')
executing.executing.NotOneValueFound: Expected one value, found 0