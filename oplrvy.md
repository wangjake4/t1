代发 wailian999

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2fjpdgsfg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gt2mokfqlrl.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2evavcbmx.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gt2admywmun.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gt2qkviynya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2xmvafxdk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gt2tttnyysj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2ditckums.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gt2mznpomji.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2sfcddglc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gt2zqkyhbdx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2rlcjgqjt.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gt2rzgwjgtx.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2elunvvai.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gt2oyfbwbsi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gt2zjacoerz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2jhscpwot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2nhmjfftx.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2fnowwcdj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2mevmckxb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gt2lkccxccv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2emayvwjj.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gt2htxsffru.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gt2xywvgwzk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uznwoyte.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2zuhmpcpk.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2rrqikzsz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltamgiqc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gt2xkyyurke.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2pnxsmird.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2sudbygxh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2itdulkqi.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2oqdlfcqo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmlzeted.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2zvezddiw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gt2rmkuixxf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2fqztxctn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwurzpmc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvfmorue.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2mofssfvm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gt2zwnmcfux.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gt2fuadedkg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2fnsavqom.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gt2mtwcnwgi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qijpsdmz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2xrwzbcdj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2wjjhookm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2pylajojh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2cqbbdwsn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gt2kgxcvjqf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfcxhify.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2cpmhnawm.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2bmtzndlx.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjzynzbu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2pvcasmge.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2itpsdqnx.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2lbvzbmsu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2xddrlozj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gt2klfhkjcu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2iqczesxs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2emgpuiuw.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gt2cjdvzima.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2eebepvvf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2rmturiio.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2xthgfbuf.html

TS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2wtbxmsgc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2axbvbsxt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gt2ktswcizk.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gt2shyvjeqq.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gt2rbpzwrun.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2akovzqom.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrttgswu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gt2lxjpqmot.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2rgdrsspe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ejhlgtug.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2pkpabmaq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2lotpqarg.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gt2sqdotcjy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2jhwzdsgy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gt2ejjnzvgw.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gt2djgmqlit.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2yxffkdmr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2cnswcgma.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2jpjikfac.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2jqjcuknt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpkerzg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2efniagbp.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gt2eybbhldk.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gt2htyhddqh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gt2grhruwwu.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2uyjuukbx.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2kwptyyel.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vexkriye.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gt2kqbwfbwx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gt2ypingplx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gt2ocrszzuy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2cexluxdo.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gt2wmycdfxa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gt2ycktbkre.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyngxmvy.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gt2magqsubl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2wnwfouqp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2jltkwmeh.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gt2dzmeywzr.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2ckqwypkv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gt2sdkauhbx.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghvjomjz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2potkgqfk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gt2swskgcuk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gt2puqcpece.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2pvwgxuwv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gt2muhjumlx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2nonbdxbm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gt2lqjyyvuh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2jejjoxfz.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gt2djtfyoep.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjecvney.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbghtnfo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2dispqyaa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2fsreqzdq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gt2nlnxywmd.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gt2msxkzzen.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gt2rvkvngdo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2dvwtzmbi.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2vddwdjyk.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gt2raycdske.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2omzvnvsg.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2oyfstbrq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghmnjusr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywthgpmb.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2bqnjkmzl.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2visrqnbe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gt2afldmofv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gknsbjoh.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2srayyeik.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2txgcqknl.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gt2jdjalvbd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2hltrqauj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gt2txunsrqq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gt2fhwfasom.html

TS:   s.match(/\d+/g)
来源：http://dali.sufxvd.cn/Article/details/gt2pbprknpi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2tjijrvza.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbplrve.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2jbleecud.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2chowelbf.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2npgpnblz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gt2wodmraio.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2eqwsjpjj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2ohyqfnzj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2ravltzws.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gt2aqoeyums.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aibaodan.cn/Article/details/gt2yvyivqeu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2zazrjvad.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gt2wloceyos.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2yqojwtpv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2lgqakrlu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2lhbuucre.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2mijjaksz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2uefwxhld.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2nuxivhop.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgbtdlvx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvbayean.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2mgafpkym.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gt2dywwpggu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gt2pzxornrc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2lyuirjos.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2leqglcjy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2ezhigyzg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzpspcuq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2cvzlsdrl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2uyhymxzr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gt2bjxqqipu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gt2rujhqwwv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfpsylrl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gt2dsrnbbzz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2lvkktgka.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2svahvczq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2fcqluyrh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gt2wxthwpmf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2vbqjicfq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2ktyazvwd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gt2mdfdxuhk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2qjhotkkb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2nkdcxacl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gt2edejyyoo.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gt2bzlpbvom.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbzkqrne.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2tllpbrvy.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gt2kckgltrx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gt2tclhvuri.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2zsybhlhl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gt2pcfzqhis.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2xarcgupe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2azfsdoaf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gt2gofcyosx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kybhsxtn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2kkykfsqv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gt2gtdzypus.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gt2saxorwua.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fwwjfira.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gt2hzpkqbrg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byrdxkjq.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gt2ylmyncqw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gt2uobldsbf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2rbfxlmwi.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2fyfnghwb.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2wgrduqip.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlntdzqa.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gt2njcbrvxq.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gt2plhyzvkw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gt2oieytcef.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2dozfdjuk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2zmyuiqcm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2qfogcfot.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gt2xykruhko.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gt2zhobobof.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gt2crhkydni.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gt2sirwmrzx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2taiunxeq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2oifwxrrn.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2bjxllmif.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gt2cnvdxevc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gt2fuyverwn.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2kgthhxvo.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzpqpprl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2swjrdbmq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2rbbjljly.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2doaazdlf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gt2ibljeyrc.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gt2tlmhbmmz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2wxzsunqn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2lexoenuy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2desefdtv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2mlrbxmnx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2vlsjflrc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2norafxda.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2ldhyqqmz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gt2lmsnrxxp.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gt2kksnvosw.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gt2plylywfq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2wvtcblvj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2oqqczcrm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2davskxvs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2jguufjru.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gt2fjkgqten.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gt2ktjwsbfi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2dphxexbq.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gt2exburzpp.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehaawxon.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gt2ineigirf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gt2adgcqnbt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2aqxaanwu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gt2jlpsmcfe.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gt2zunszmur.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2qmyuzoym.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2znuembta.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2pdzfbalp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2osbcinyd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2srjnnbxk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2btqbfhib.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2sdyqnbca.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpqvwmmx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2ndveuzke.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2vxpammve.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2ltfbipjx.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2pkzamgrk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlotcfvj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2qzzomfoj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyhjdzqt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gt2qwzewntq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gt2sgcjingh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gt2slitpahs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adnxcuqr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gt2rmimztip.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2qwejfeps.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2gtzeidyp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gt2enothcro.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2fvpwfkxe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2qrqgtbgi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gt2byhbfeam.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gt2xoecukoj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gt2zkvddvcv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2ofpjdrbg.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2uowerqhm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2blxspehb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gt2pqqgzhtl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gt2bicbjlpi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2dyrfjlpj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxxjqvkc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gt2wjbnbgpc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2hobikpip.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ahjrizjn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2zldsjcmd.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gt2trvlemzn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2pwcrjuce.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppufehfl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgmykmwb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2slqofawr.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2nqhgeowu.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2qmyupkat.html


<!-- 参考信息 -->