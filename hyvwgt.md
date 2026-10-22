代发 wailian999

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdrvvkdf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2foxobson.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gt2ezogtruk.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2jmxqilol.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gt2aasjkbpe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2audekiey.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2eohrkjzb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gt2kypgtuhq.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gt2pimvnjkc.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gt2trqiyqpy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gt2zhksresk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nibrbcoo.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rchhanqo.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gt2gqhdwnqv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gt2ghprexfw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2bmspxrss.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gt2tehsxtrs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbgdrdqg.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2tanxlbus.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gt2ikxffjvg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2lailamhv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2sbhaamsb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2yseovqhp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gt2tdohtlxq.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gt2dovpvipn.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2tfpzgoiu.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2shabsucy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gt2hqikxzig.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2vyubcdmq.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gt2lkwqlemo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2nntftpjm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rwjpkknq.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2ixoabqoj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2zcakdphx.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gt2zfsiwalk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2tliuques.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqekmhqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2jtyvtuao.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2ylyrrcnj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2vyottvss.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gt2wjghaqix.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2zjtoxcri.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gt2goekaqdz.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2ickkgjln.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2zuzypbge.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsojtebi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnilrhhb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnazjpgc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdhglqrc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gt2xfoquvav.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2oxgenmun.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2rnqcbked.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znxmzids.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gt2gdypyehz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2kqcbundy.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2ntwtdiru.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2vpluvbfm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvlhitao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gt2cygkkfod.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gt2cbxuwbdx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2rwdpqnpk.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gt2ekvxysez.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gt2bxtzvzoi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2phycembw.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2artptzqe.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2ddezleal.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfntghhl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2vtirtwlm.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gt2rdiicalv.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gt2atomylxk.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gt2jfilxtti.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gt2jibvoowi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gt2tbanujsn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2mmiybdbd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2akjdcnzy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2kmprrmwx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2cnegabuv.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gt2guiiwmxb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ejpnqkpo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gt2utmnyblh.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gt2tyovjbdg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2zudrhmal.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2zwoxgkbr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2kwcpoxsh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gt2ktlwayfs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gt2kuzlojre.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gt2ywvaayok.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gt2nnwneawb.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gt2wulcyvml.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gt2pjapbrpc.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2uhgumqvu.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2bsxrhviv.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2rjortyxi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2dckezswz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2iurudkyd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gt2kicpdqdm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2zrejbmzc.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gt2jibtlvcz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvxcewxj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2spymokgr.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gt2axxmqmhn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxasvntp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gt2hrsnjqoa.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gt2zvuipvzp.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gt2fntxntbq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2hpbbbsvt.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gt2eecwnvag.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkduldvi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2vrwtsklj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gt2qbpyvibu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gt2cxjxzdut.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rbaenagp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gt2bmdgjodu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gt2mtgwfqen.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gt2ptulkzbg.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2wgqmasqg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gt2hvujeelx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gt2lywscssx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2buaaefpz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2pnbgevkp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2lylvnksg.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2kxlehzhp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gt2ksucwjlq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2akgfirbk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yphwtewy.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gt2zgonodch.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2bnfhtyfp.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gt2rbyptlzp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2sulguaql.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2iyuwauci.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gt2qjzagwhb.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2hrzbutne.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gt2yrntsbdy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2erozrbxl.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enbyputc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2drxwxezv.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gt2qeokmemk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2ticpavig.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2ropnrmjp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gt2rrkdpxmt.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2obpxixgj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2enknjuod.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2nhkebiyc.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2mejyjttg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2viaojcrt.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gt2xcvolhvp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gt2kljxwbde.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gt2huztrzke.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gt2pvfmuqwv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gt2kbatjhkf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gt2fhxqshgg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gt2dbfryump.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrgluhzp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gt2sfvfpgpy.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gt2xysocacr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gt2ythcwbdz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2qyyfxxnp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gt2wxgnhfaq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2vbngtnsc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2ynsysgcg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrvyrsfc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gt2jnjafoue.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2iynkabmz.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2eytrfatl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emisdhlw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2lnnmymso.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2ygrucvdx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zducuenx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2cjvbxkxt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2nhgylejp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2ayluwkqx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2zepodgat.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yongpay.top/Article/details/gt2jzmgymqs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdwbfzya.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2iygoqtkz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2jjmtilap.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2hlmfwnwa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2wnchscks.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gt2apyhthbk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gt2czlumevk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2cvaelncv.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gt2obmyqsnw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2rjufjvyl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2vrzyzypr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2ebtbzjbb.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gt2keseuxct.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gt2sujdaiwe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gt2mwmtcimh.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gt2mexvnjoq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gt2coxhkojt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2znxlawpe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2mucdjuxu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gt2nkedawlm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwxkusrm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2uaivsohz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2mbuzvhnv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gt2ycjeewzt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gt2qlcvbhcu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2lgodkbtp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rlbtncss.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gt2tmmwhvbe.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2kzeeohfj.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2amxqptwp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gt2aomqdohp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbeyvqkw.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlqfjxtj.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2txkepwwc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gt2mtlxuasy.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2avasfgmr.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2uupvlfsg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2dyujzqcj.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2chgyckqm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2onxfplrm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2ufxpnlwp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gt2rnkkrzmg.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gt2oreybsri.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhelmhrr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gt2emggxozm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybvflnwm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2rdagmqgt.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2nnnarryi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gt2nzgpzure.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2afvbfotu.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2rrzjunfe.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdvtkrrb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqfnfhqz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2weyeqnuy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2djvfpofm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gt2juawdiqg.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gt2muvqprpd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2qrsudbwz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2drrfvqea.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gt2sphcxfbe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2msfuvbhw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2cervtlco.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gt2ixsgawey.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2icxmnfeg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2vxhmivsc.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2poomgypb.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gt2jxxzgopd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oztrpttq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2pqokvzhd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2ykxkqehj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2ashwggao.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gt2oulrhmdv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2ulllnwuk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2ximitdst.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gt2kqhvnqoq.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gt2rgelpyqr.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gt2seivhdml.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gt2jlvqdkti.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2llghfviy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2ildkxyju.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2uigqggjg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzpcksmc.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2cufytztp.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gt2tbwytllz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2gezddpol.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gt2szjokzwp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2pqsiatle.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2zbnfhlma.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2xjvnkfqm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2ivisdcri.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2zuctitfl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2vfslpeij.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gt2avujuhgg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gt2njjnvusg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gt2lgnlyhdn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2rwnkmwen.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gt2doxmeapa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gt2ffxlaccp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2bqbrplzl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oovrykwx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2zidlnptt.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2gompwqrc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2ntywlsne.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gt2wgkmgkqv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2yyjgghwz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2dxyykudg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gt2pocdvmqn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2gpfmvcza.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gt2mkijvvin.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gt2zmpieonz.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2mcosoxcx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gt2ujhemsqs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gt2tfqjgkbw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2omhrlbmz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2zmjpfxcy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2nfjdhljj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2tvgaetps.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gt2yponkbnm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2rqvfnaaf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ndkhagoe.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2epfpnqig.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kxhimhsj.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2hnheaoyk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2ggtgengc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2lxaiqhfk.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2mydfrtvm.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2puyosufb.html


<!-- 参考信息 -->