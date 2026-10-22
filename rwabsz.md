代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gt2hrctncti.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2ogqzhqdf.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2aqykpzux.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2cvrprupu.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2pgfbggeq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gt2rnwxpkff.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gt2kesiuosx.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gt2trtczkib.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnerrkdj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2lpdbacbv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2hzopnwwp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gt2wvdmckyo.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2tkrsgqsy.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gt2wmheouwm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2gjjptbwp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyjiwlnq.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gt2tfdqdabt.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gt2crmvqzsi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2rwafwcjf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2absqfolh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gt2hpriqpxh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2scvhpkue.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2udaddtie.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gt2ahxibfnt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfiguzcu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2teenxfyj.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gt2bidunzva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gt2mojrmcso.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mykanilr.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2qhgrwpxt.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqtmfnhl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gt2wgbsvtdh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gt2lqtgmefs.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2witbmjyz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gt2sqieftnf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2gudztnhe.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2cfhjeiml.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yiwconrb.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gt2mrldwtvr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gt2ilmoavtq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihzyvvlw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2phqdlpdv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2dqesejxf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gt2svjarzsl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2tdsygzms.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2xalzkbdn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gt2ipwbqpho.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2pmgalxoi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2ygboxinp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2lteekzaz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2lzhijdnv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kggpdvrk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2mjdcvvbg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gt2cldkdgvf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2ljnxfoxj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2kkzflhdy.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gt2mqhhnlgv.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gt2xogcgtrv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2kuulwaas.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2yhyaoqwk.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2cvhxilji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2pqbkulpx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gt2hckmfyft.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gt2npmszjtl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2selkvhyh.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxfyfawz.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2hvjfogcc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2tbbucuoi.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2bjoprlqt.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2yixrqrdk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2jhobjzjt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gt2hudendpl.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2bsyvbnnf.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2silthmas.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2hemrayoh.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2mtbuhcdf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gt2higcvetw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2fxpnqcao.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2wunoqlku.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2iemyppcy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2xnfgliul.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gekrqluu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gt2rmcjzkqm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2vcsxpjec.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2onomifbj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2gktwnpbv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2vqgctgok.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2puvtywuf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2wtnhstsw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gt2qnbxtfei.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2hspvnjpj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gt2dcavfhhz.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gt2lsfhtive.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2sywaproc.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2thpivekf.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2mfprdwop.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcqvzajh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfnstoxb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gt2enrlxnag.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwrekins.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2rwdqieah.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gt2qnilrmub.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwyxtnvv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gt2jlxhhzzb.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gt2ioblvldq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gt2ydpqlqyn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqjqzoky.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vughibah.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2nsazbtcp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gt2quuixxhm.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gt2rpzgknvm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2hekhbeue.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gt2ataijhfj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gt2zudifmnu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2aznzhdoq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gt2vvyccwhz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gt2ujjzdpiq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjxknzzr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gt2idxetimu.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gt2aiymuoaq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2aifmjsjp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gt2owkuiydz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2usjibgpp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2fufsvkro.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gt2ydgvyrjk.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2djfgenjt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gt2fnmyeaeg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2wrreieyl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocpzfuac.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2iofxktrs.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2znfbcxyy.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gt2whjskrwn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2dzsqriur.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2zwiwdvqe.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2slvlyaeq.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2qnelecfa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gt2yhwqgesk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2cwoafrja.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2xlpkdrqk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gt2yhcsmvxz.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2rdkpjjru.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxoyyeil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gt2ngdirnsp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfqgbxjd.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gt2jcycvlhs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gt2fwtnkrfx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2jfqnsgau.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2wmfzcnii.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2allfcshb.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gt2erxmxkgj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2uzauvqlo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2qhpwbkyy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gt2jrdjpxqf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gt2mrnwezrt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2iuwozbsn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gt2ktaincuu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gt2dxvzjpdr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gt2ldcwmycz.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2cytszjve.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2mswmlzzi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gt2qaafcnqu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2gnneeyaf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2wouaynyp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2kzflthhx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2fazqabzv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2fymkwqmq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gt2gtigcpwt.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gt2iugkjhgi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gt2dortrlxv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2gwdporki.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2rctuhaaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2jinwidaj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gt2spsivpqo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2kubicfjl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2lspxtxug.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gt2gowzvmtv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yanxiufei.cn/Article/details/gt2xwprxvrf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqndlxol.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gt2jnizvjvy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2mqqzxiym.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkqjffsf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2zxetibub.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gt2aujqonbk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2nxgxpqqm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2lfcuclvp.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gt2urzxrqzj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gt2ijbpvoud.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2yydncxkp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gt2gtfsyika.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2mgzvdkod.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecslvsje.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gt2ukkhgasp.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gt2zulbvwdp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gt2sghvbmvy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gt2xxozunqr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gt2ypadkrsg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gt2ogrcgxpx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2cjpcgdqx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2qyokarpn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2nsypgkpq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gt2cwviiihi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gt2kwfninog.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2dpakyaig.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2axwlpwbc.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2ytitraln.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ovowonkn.html

[J01] 获取当前时间
来源：http://dali.xylfe.cn/Article/details/gt2wcoztair.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2hzcpmipw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2pczerjdi.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2egymfyxv.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2zlsyhuyh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gt2qznhobrw.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2yhxwwkdq.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2fzddudiq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gt2einelnrb.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gt2lzkkmuaw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2bwejemgk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2fbjrcyhp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gt2dppmhmwp.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gt2uxlllmom.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gt2qvxjfzvn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gt2wcdgaqld.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2larriqaw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gt2rzdfjljt.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcsaklyu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gt2mbxsfsom.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufuzulel.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2rviuvvgo.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2hbdiuavf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxfdujzy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2tpcimdmi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2sazmhjqj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gt2rzbcmemi.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2josdnvjn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2trformhp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gt2tugpluip.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2lhzwbqkg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2ngselmjx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxgrndtf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gt2yxwwxbgb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2sjqxgtyi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2hsnaoshk.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gt2oaommdjv.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gt2ntwweflj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwfswnsz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2psyhgyun.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2unzgoyry.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2cdsvlhjx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gt2vooflkrs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gt2bpkrmxoq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gt2gdaknhdv.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gt2kyndltax.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gt2epnrddaq.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gt2nkkkoleh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gt2rnojsyaw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gt2fbuflppr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2soearoxj.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gt2wipotuty.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gt2rmdlazrt.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gt2sdaosead.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gt2gsfjhkvi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2cxtzbbha.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gt2zlnzazxi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2aitixatf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gt2udxtnfzs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2gxwguxin.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2nnxohfxr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2bftevuyp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2dfglzgnz.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gt2ymntjlgh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gt2apfqyhsv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2bqzymuuu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2ouwrejsa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vckcxdyi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gt2ucabnkto.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2uiuiupmp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2ospxqzvr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2lkkinbio.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gt2jksltqrz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjwrcazk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gt2bwhxjxhz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2blbqoebj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2dquobhqa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2kueugmtj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2uqwxszbf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gt2miwbagqk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gt2wjnztztc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2nnjtocqv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vclayexr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.andypj.xyz/Article/details/gt2wztdrzcx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tezmaudo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2wjpqgpia.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2hngwecmp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gt2ztfkupdh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2jdshchhi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2tohjjyzn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2tasdraev.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gt2zayttrnt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tblxxuyb.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysdylabs.html


<!-- 参考信息 -->