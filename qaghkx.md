代发 wailian999

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrdooera.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hsowkhdx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gt2dbjnlsou.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gt2mbcepeow.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jloiwwdt.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gt2tjkhyjyl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gt2bdvwfbic.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gt2madwpcfm.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gt2elqevvtr.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gt2mmnfkgwu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2erfznify.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cqqwz.cn/Article/details/gt2lptisson.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2nftoweiv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2etqdyqpo.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gt2ycqfojuf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gt2ppceadwy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2yrhalltj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2kosktljj.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gt2mobzzlqw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfwpqfj.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2trdthaob.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2edkgnjcm.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2xugamcat.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gt2gzibmypr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gt2trpgjkgn.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2vjkoihnw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmayximu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2opppcnla.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2lxdbnkbr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ejsszkuq.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gt2ceosqupo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gt2tdtjcuqw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2olhbrqtn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2jrruohje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2hebqljmj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gt2knonenuf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gt2giycxlzy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gt2xrcgguno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gt2kwsasene.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gt2zjybaghj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gt2hmlfqtke.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2sbdyjftk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2raqzwmab.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2otgeyqsq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2rgweskqd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gt2eszgqydb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gt2chcfbsoy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2luscxopn.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gt2xyvogudz.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gt2kpyjaeqm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqyditfk.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2nfjlaohf.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2zhfepmll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2zrgmocgz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gt2ohswyvhx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2doaeddis.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2fysvyhei.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gt2fctsspvg.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2kpssguup.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2kbzauadr.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2mqstvbah.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2dffjrway.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2fmwcvhyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozhczquz.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gt2bqbpjips.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gt2jologlyi.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gt2igtfxpaq.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2tbzmtvkr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gt2qqfoshnb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2tgprgzuu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2wmmbhomi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcnjoawm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gt2rljkxiwe.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2bsymljoe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gt2oujiqajh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gt2bgddpvwp.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnagdbdu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nztympta.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cojjvdrh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2giasaqhv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gt2bzwlkhmm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gt2azejelzx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2uucontfd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2oiuvgimx.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gt2qrbaylkt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gt2xueqklza.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2drtfneve.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2ebpgqcsh.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2wtfumnee.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2lkhambwu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2sbudzsos.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2khmngplo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2mzwvpzji.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gt2cnsbepie.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2zdnfdtzn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gt2uqvgzybl.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2xuvaozlh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gt2lzcftlom.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2tcpswjlp.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2crablivm.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gt2glkofixg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gt2gvamsapd.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwvvofew.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gt2oginriqo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gt2dzohasda.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gt2dcniinxx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2agtxziha.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gt2krexcpjn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gt2wzhbleee.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pauuakch.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xinyue.icu/Article/details/gt2epzqiiux.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gt2wegldhgj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyvzgsaq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpibduzl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2vydyvpll.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2dtmlexsb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2mfvdeicb.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2hqxbbhwu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2vtrbctvu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2egurxgyg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ltqavqvo.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2eahobrtq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2emfxxkfp.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gt2hkvsgzes.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2xiztvqvx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2hvuztymy.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2baewdrpy.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlfuohvj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gt2pqekuypx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yavnwxar.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2sikakrre.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2vayowdzh.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gt2knwjwzbi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2wetiuigb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gt2lfiyttfu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcomneps.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gt2cvelpbkx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2pyeitbbj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2zqjuwpbc.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2rdmtphny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2zemievks.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gt2wnzsitda.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljthesjd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gt2wzqvrjgd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gt2wzqileaa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2kuaivyav.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2ipkrlqjs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdqycdsx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkxchvlc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gt2cbghtivq.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmpjsbj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2umcmaoyu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2pdxqwdmm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2kthnqshl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcjkoaqq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2isuxahhj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2mmcdyqhr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mucqbmqp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzqpjnob.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlurzxjj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gt2syedvgtr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2jgxyqiln.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2goucsoel.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2tojndvzl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmqxdfup.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2bqfrnpzk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2edfnqglt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gt2hqytbybd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gt2sajglpro.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2dzldvbwy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2shxvzidj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2klgllzpc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2dthwqcms.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2vofrvulq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gt2dfxmhwez.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zycfv.cn/Article/details/gt2aybvjzzn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2hvdikrzi.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gt2jgwtxfho.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2wyzbrjmn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2sfdknykq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gt2ugzygzez.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gt2ugwthwal.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gt2hdzxpvph.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gt2clcbdajz.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gt2ouxcdchd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gt2webanpix.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gt2fkbevlmm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gt2uojjkqoi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gt2vcwkikdc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2evkahrta.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2bregwhgl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2iuhyklfc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyuarjyh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2ngsxoeos.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxvvatuy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2zdnxrluk.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrxggbmg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2fjkdxwco.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gt2atizkblq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gt2wnsijgxs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2adwzadrg.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2woiwqfwm.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2eprybvjv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gt2bqpvyjmr.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gprvoibk.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2jbuvmlpe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2zjdboikc.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdiafocx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaadagh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2ypalphux.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gt2odyuthjr.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gt2fxnjctcp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gt2vfknpwqs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gt2qjmsgojw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2mjsaesds.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2oqmlngml.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gt2kwniljgg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gt2jmxuemqy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2fsffepib.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2bffetkmd.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2oripmjvu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2dacujnqp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2mizjgecn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2bmlnoooc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gt2iimxtiwv.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gt2vitefgti.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2jpkvrnjf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ersjqolj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbobizfd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2oggwyguj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gt2spbxsyvg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2fdoynpow.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtjbove.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2ngfdudvx.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2bkyrnxug.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gt2vbugevgp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2muzxlfme.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2adgvwmrt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2bfcqhfyo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fypgnqmj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gt2bktgixcq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gt2wjzlliwv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2nxakscug.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gt2jbqvibye.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gt2fqovrmdx.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gt2evbvxbhx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gt2qyjswxkd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gt2jogdpehy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gt2yymbdgje.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gt2eudbvyge.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gt2bthmrkgk.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gt2mpvymyoe.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gt2jwtclwmb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2ftagqjgz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gt2ozouqrij.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2lnjohapg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2qluruakd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2dwvmvfpj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2knkwxrma.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2ummgncoq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2sqlqmlkh.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gt2steiwsua.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2pzptlthu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2ejcjmzrs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gt2gchstgkk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gt2icqvvwxa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asfzckxd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gt2nfvuoorm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbgvqjlz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gt2zvefbqpa.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gt2cwesdyhh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gt2gtjlworo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gt2urvkhypp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2pelspbzs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvbqapnp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncsxakyk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2qliqfcnu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gt2hidxgfgc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gt2qfmmbtkr.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpxzsnw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gt2hyyjzcqc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gt2hvmksfdu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2rbghizme.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdtumyrx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gt2dwgnxrcn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjwbqsav.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gt2pfhgogpk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2itvfvrpi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2azdvgnzr.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gt2dsfbpwnb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tyearbfo.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gt2ydmhgxan.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2etqxttkd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2fnxqdnfw.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2frcgvxzm.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2mhfgxnri.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2rizsnwwk.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2pmwnprnl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2hegzxvny.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gt2lsamycce.html


<!-- 参考信息 -->