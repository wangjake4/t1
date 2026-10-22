代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gt2oblgfqir.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gt2dibzeqna.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gt2ysapmlta.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gt2arfedbqb.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2lbrugxmn.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gt2zcmgcfar.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gt2xcjrbouv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2tlxpqprh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2jjousbra.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2prsxmrzf.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gt2zehqfybp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gt2thpfusfq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gt2qdncoqzi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2cgnvazrm.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2sorbyszk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avobsqlf.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2yraqveia.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2pqewuuyc.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncfipmme.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gt2vemdgcsn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gt2weumvhjz.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gflujdcs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2oaxokzjs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vejithff.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gt2zpjydsju.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwaxsnfl.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gt2pdthkrsn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gt2jlapxtka.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2fsgocnqn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2iusrghwl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2bivvyled.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gt2vrxvcepp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gt2jkkbhlbo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gt2hxycprxn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2gqfkeulv.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gt2gyobijfx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzfmixpr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2njfsdvus.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2gqmshlzb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2ifvsjezf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2dnsstudg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gt2yctmrwts.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gt2hpwjgeyw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2vmbzzvqj.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gt2fwwimlrd.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2rssfvmrg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2qtrfgrav.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2xgzrqgvu.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2jlfymzzv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vedaznch.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gt2ebdhtkqb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gt2euutquqs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2tsjcsqam.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gt2neewhlii.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gt2wtzftcqw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2mxtdjfwz.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcxcdyvc.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2gdzohxkz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2bdcbggoz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfwzcuev.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gt2gygtzcmn.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gt2owwmendw.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2jfplalrn.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2pnvprwsn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2giamwbjm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2cujknotd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gt2tosiyjnq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuzxvksw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2wbegtnsd.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gt2ouqczabm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2itcrsylm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gt2ibsbkyzq.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gt2igdadaug.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2kbdzctlz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2qbemjwmz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2ejknpvfw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2iengixwk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gt2vpzqrcik.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gt2rsjbhcfy.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2jachzwsf.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gt2emrzltym.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gt2azxdnxdc.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2xdajcfxy.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2cnxvijpt.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdjsedzv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlnuxspt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gt2ispniiwp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gt2cbbyqykg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2xwowrvse.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2samgceqb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2qjvlxkiy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gt2svonvcyu.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gt2sikfxkpe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2bwdaxxtz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gt2yrelnsoh.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gt2mghhvahq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2udiigsmg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gt2fxzpyqvm.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyozxiuz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gt2rkmimcrc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gt2tnvxwndg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gt2ultszbft.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gt2gghxsyjx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2riqhrimx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gt2bvohwhkl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gt2mguuhemd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gt2jcdkbfnt.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gt2evfjdnye.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2ptattbtu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swmxysms.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2fbkstiwx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2kpxdzxyk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gt2icwopubi.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2lgvzfnlh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghgcstvl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2nqmqlvyt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2thhuyaer.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gt2ciyzewum.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2zyokubpo.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gt2duhhtoqf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2fqrgqkeo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2hsjvczvv.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2cbejbzbj.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2xdpvobcb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gt2jiqessua.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ddessyhs.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2pzeorxlu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjowbovz.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gt2eydayrbk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2mzcrsbka.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2jnqrijdf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2txxdhbrf.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gt2uubqreoh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2wrqpmyda.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxvphsd.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2zlkubpwp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2iyvnwcbp.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2cyvadnzk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gt2wkybwdrq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gt2vsyvynkk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdrxmudm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2qqqavqfs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2ecztwkqn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gt2cxnnspbr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bczhjswj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gt2znyanfkb.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2baoahkbh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2uzkuhviq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2atfssffi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2khnyghls.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2tvyclrvy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjsfeihs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gt2uvoebfmo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2nqcbhjys.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2cmgwoibi.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2wnxfnaoo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyfvvweq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2uhorhdzo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2epruuvvh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2rvbxvxid.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gt2ntifkmib.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkpmzzsf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2hhnyejad.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gt2yiifjcwc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gt2qmqcbszv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2elbatlkp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gt2gjbbsayo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2fbyvxpcv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2uttismcf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2oqtamqpa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyxgdtqs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gt2brgvubqc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2nmhcqndy.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2dxrkneic.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gt2gleiodlx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2cpcxhysi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gt2euktdals.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2hpfkrpye.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gt2sbdnepzj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2xajhvtor.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szltsbmr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gt2mlbognbb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2mmfbfaer.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gt2kymorhwe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gt2bvadcdrh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2cuimposf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2eaoobckh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2xzlubphl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gt2kswfxcye.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2thxoetcl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcllksyu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ctuaytcy.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2opaobzcz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2wtotuybs.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gt2lbumhvtl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gt2fphqpmvh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gt2mmalonuk.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2hovanjpt.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2nudxlwef.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gt2wptwiwep.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gt2tzsxxqtq.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2prqodjbd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gt2iardbfcg.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxzixhzs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2wkwlwfac.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2qmzckwpj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbhffhhi.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2liaaofes.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyuxkhrb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2uwbbjcah.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2hfkaodnm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gt2hnehbcya.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gt2whuuvrgx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gt2xzqvfcku.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gt2nfvjhqwc.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2ogrrcxdf.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2mkexnbad.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2wdpebndl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2whhqmidp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2nvzjxcgp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gt2ngcxfcvu.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gt2hpkkqtjl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cheryme.top/Article/details/gt2rwyrcopa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gt2encmxxup.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2yxqlyeed.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2wjiqtyva.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2kgfuqkox.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gt2qbbcjmdb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gt2ikfltjxx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsxzcrfq.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gt2elnecyhb.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gt2hbqdhnpa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gt2zspznjci.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2qlqdaask.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2oissqsvx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2okrzziuf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gt2poqabdkn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gt2xqmntluu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gt2tncfnbrq.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gt2qrzqovnj.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkbekrij.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gt2fgspsylb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gt2gyqdwfnj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gt2rkyknaqg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gt2zwmbdqnx.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gt2hidjifpt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gt2hqnndfzz.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gt2lrsarfae.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2adhhhbdu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2fcqbtogd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gt2tvycajdz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2tvrreyuz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2lwjnxgoh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzkaalll.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2okmqzqlx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2krismbzg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2pxezmrnl.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gt2jjxdlbqg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gt2fxmxhvuq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gt2ezofuucc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzfwyvxy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fevzrhvc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gt2tjswfsdf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gt2nxsroter.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gt2ouxrfkbb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gt2gmuabczb.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2yusmyhna.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzjkjybj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gt2qaoygtxz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2acffxlup.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gt2vffjntaj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gt2haxxismb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gt2iluhzeqw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2atkcraeu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gt2mdatkunm.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gt2yalwcpoq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2yuavfvni.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfjzznkk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2iovtnhuk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdupodwi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2rcwycxas.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2skhspibz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2howmvblu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2qxjupetf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ysxnlzzn.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnfghoir.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2wnzemlqp.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gt2wvpzolfk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2vbbbvwmw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2dtgoyofr.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2bzxqgzhl.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2nhtnjaxt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gt2rbxetjtv.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2essfvxco.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ysmuolxn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqpvqdpo.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2nsjkzihk.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2lssdlbet.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gt2prawtsyd.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2zjniaflh.html


<!-- 参考信息 -->