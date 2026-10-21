代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtcxopfdfz.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtzwgzrged.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtsognkyva.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtiypcsmkb.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtvcklsamc.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtuagkjsbc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtedetwdlh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtxkonaevb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtrwaxarhf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtjqadlgdg.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtxvyiwlfh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtmqhdwjwl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtfrjrdgks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtrfzhgdfd.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtwfhpsckd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gttlasaebm.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtnwjrofnv.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gttvetiqnm.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuxldhjj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gthvdcjkyy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtwegshhol.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtegqrkwqu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtybljxxkg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttnyuakfg.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtrvrgwogr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjmmxaslk.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtnfkrkxlb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gthqfyjkjd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gttrlhyeqx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtnbbgvurs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gthnwsbvni.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtmmavozgw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gthusvnlxw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gtichuftiv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtlurihabe.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtzbnavnqq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtcibxzyfz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtdjmcxmxa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtnjwcofrk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmariokzu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtlbwfijmw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtolndnqeo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtltfloghe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtuxbiwlzr.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtpjmcrcja.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gttifyoril.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtbdtqqwvk.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gthfmksptn.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtgghmqujw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhiyaxub.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gtfryclhwv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtusnqxyuk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gttibtsocl.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gthxylwnqp.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gtimkyaavv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtpvnqvqwz.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfovfrhy.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtvpqaodnm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtggnspeoy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtenrzrvmr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtuoswiqiv.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtixquiaru.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gteopyikog.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtouyyzruf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhqbpkdp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gthxalmfnf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gttvjutong.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtgiucwrdi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtydtefpgl.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gttzjgrkxt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtyusljtvd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gthfaupmfl.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gtlzlebbul.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtjvncmstl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtwophkipu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtwnqsxetj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gtkcrcamtg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtbvlcuemf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtaordeylt.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtbscynacl.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtiibqksly.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtnrfhemup.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gteaoowxzy.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtafvvqcuw.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtpxhrjoay.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtwbkqyvtf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtazeczlju.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtkiwnmwlk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtjavinxwl.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtmxrnauhh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtnerbutry.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gtzbcqdwmj.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtctgsbxrm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtpunhjtwv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwsuqemy.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtyahhwwrv.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtkipblsbj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtvqyqckau.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtgqyjcvcz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtpprrvtyv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtkrgyrmno.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtusqgsikl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtxknojgjn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqyhickb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtsufjwlhg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gttcwxxgsu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtuiwdflcg.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtyldmdzdj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtnulrbqsi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtsadcuiqn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtyrihkoyu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gthhcyplkk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtauxymoxx.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gtmnggewjq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtbvxqzlel.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqtjuqcex.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnrpfrvgb.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtaklaqvvu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtpuogbxis.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtwxebifun.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtnmigjtxp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtjajrdogk.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtfoyquihn.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtohbtlepo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtdrzbibto.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtrlqasffx.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gttmarexva.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtdhvmvnjd.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtnivgxyfk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtaikzfgtu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtijhlmhho.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtcbgkrumd.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtupwlalax.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtustvlspj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gthsramlfd.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtwnqowlbz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gtswijxdlr.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtfuzkyuqh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gtbozhmbfa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtoofvvkmn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtwuilomvh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtrrqbssug.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtrcgozxnf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtvhjlkiqv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtqoopfddm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtmxfjfcpu.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtdmrbuyro.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtoifogywi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtbkyifdtt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gttbrnzkju.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtnwbsgxxt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtjbvhvztr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtursxvtol.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gtrdjatoio.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtkmlyxkxr.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gtlqvqmseg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbahqxwg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtubbojyvv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtfhkypqxe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtjjmdhsqa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtiycllnvs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtlhmzbwdt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwmgshxg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtcnegivox.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrcaikuo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtinrvrcug.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gtrqwsuadv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbmugmnk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtswqpgbfy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtrbsmzlhb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtmqqxzkqt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtrgaorqre.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtujmuncbm.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gtrfdykmsi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtnpgaimtd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtcpxxzeyd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtewqifqfj.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtxczjzupn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtzpeselie.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtcdadasrj.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gtlbwtlwor.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gtulkgsxpa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewlnkxol.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtwchpljpa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtyopfehez.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtljvstvkk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtoixxivjo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtmgetkjlw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtvjjfjvfp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gtkerlhlsg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gttazyfoxj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtorfbrpnn.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gtmvznrwtb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtyjuccdno.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkwjhgee.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtyehukroc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtzrqqkncs.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gttrebdhdm.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkojdaoi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtcxsdkyru.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtgfaowdpu.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gtrcjucqew.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gtftkskilm.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtkuiyzgkw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtiqfgyudl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdilogkz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtndowsfft.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtgtqvthpa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gteaffmxoq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtobbfjnuj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtzqbkefqs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtmptufieb.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gtaoftzmkb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtsbcbguyi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gthqsrfsjh.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtymmatfkm.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtmhobxvjc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjwxvkjj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtevnjyjrg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtxuswydiq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtlpousgia.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtficekymr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtusdfkckf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gtapnvtfdo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gtrjdebwaq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtucswcksc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtgfktenla.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgicdfskn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtgtlojwzs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gttzaqsuam.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtaeptjest.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtkceycene.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtslrlmjcv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtijiqykuj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtelmlwydt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtqmmsrqmr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtwwejovth.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtxtkoeufl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gtduylobbw.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtfsitgvgx.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtlrjmrhug.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtfpxozwqw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtemudfsru.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtbshyiugd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtdddgildz.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtvrybehez.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtjlagwece.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtrmnzkiqi.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtbvpogpho.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtpuvmwaha.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gtypzsevgf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtobpbwtue.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtwwzpwdpn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gtxcejpudf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtcgyqfvtz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtdlnjcdhx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtfnypjqrr.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtybvvsdkt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gteunppwth.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtaawvnhth.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtvksaenmm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gtmkxcjxhz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtuapboria.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtkgpinxqf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtrgpmaoln.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtqxrzmldd.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtzlwdimqa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtlxlagyxn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdnuyxyy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtbppgrpyk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtfxljmffp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtazpjhkqz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtsozsyudc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtpiweekxt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gthxiqsjmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gttgshvcvk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtjeobldxq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gtpdrsfrah.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtotyrvfrn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtsuuexuck.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gttjcwwncy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtqxpzzwgc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtyzdmewpw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtlrphishg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtehbkawyf.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtxfwpiinp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkhdnxehg.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtyyknwqmb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtvarapukn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtmejbxdaq.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtnepnlrls.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtdlzqntka.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtvsrcbjci.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gthiwmfyoy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtgxrchdpc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gthwlkozpa.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtmxbbemta.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtcaxmrpet.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtywmzocsi.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvsxluyz.html


<!-- 参考信息 -->