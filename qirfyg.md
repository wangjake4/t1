代发 wailian999

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2tapcgrlu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gt2lmlnzjsz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujwovbcq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2elihghoq.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gt2lwlemppd.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gt2aniqbrpz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptdvkimd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gt2yqeozwhf.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gt2exrzfytw.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2hoyudlpg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gt2crbmbomy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2xfettave.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gt2tdshupse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2xgvysnby.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctkzmbup.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gt2ibrutnmp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gt2nblezrnj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2arfrrnkf.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gt2wmrlvufe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gt2zxixbdmb.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2wbmzbygm.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrtiajnc.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2mcmvrrcw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzeptfcd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gt2xhrxuiln.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2yvoehmif.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gt2wveqfkdk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtckfuys.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2lzridydb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjqmcsod.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2mrxhaloe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2pittkyrn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gt2wgrxslwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2efedtudx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2smmrcwvl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gt2azkmhdna.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gt2fabrbmtp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gt2pgbzjqax.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyverldg.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gt2zrwpevlb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gt2lywmkszk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2crqshays.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2jkmuxgws.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2jhdpkaov.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2wiscbmcb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gt2qcriezfl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gt2eevrezoq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2popofert.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gt2wlvcmpdz.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2rgqjsgxv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2agxliczr.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2tsykmegs.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2klacdkib.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycakpsxf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2xyybpvtq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2kbhtopcx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2tisncffb.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqmaembd.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gt2ditpkilk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2nwwqxwve.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2nzsclyea.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2qujskmdl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2vzjwwvlq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gt2fdgsfwfh.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gt2kmhilgmy.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whnunazp.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gt2jmxhhugj.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gt2nbxgnhqj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gt2fholdsjq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2twhmcdhs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2pdggjtgj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2bflmirbs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gt2liaexpwe.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gt2iwfveybs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gt2llofymhx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gt2irwprati.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2xshxwfzh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2zqcdailq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2ztixerls.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2yjknject.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2mdwivrfq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gt2hdjrafnu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gt2ihizsprs.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gt2jkhrkomi.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2tuzcmvxj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gt2pofacmde.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2mtzcglex.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2gdpbdqxa.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2ojfdnain.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gt2wcfmvwvv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gt2onwlkrpi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gt2lsshzsce.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2ftpwuomi.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gt2pmijmvao.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgchycar.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gt2ntpgaptt.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gt2xuawnxwl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytapdemf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gt2aqllzyrp.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gt2yjgzfufp.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gt2bdjvngeu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gt2zddlwzxd.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gt2kkbvodby.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gt2itmrgfxp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2koddarkr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gt2ibilgwjo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsgmxwyl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gt2swpnhpcf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gt2jeercqdv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gt2smakhvxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2iwzeihsj.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gt2qjgakddo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2bjpfxsae.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gt2gmhrejna.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2arwbuizk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2yvnloxag.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gt2bsjgvekv.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2zejpglty.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkifenmi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpwwxqqb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2kixifdwp.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2guwzkmae.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2lfkcwmvo.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2ciekgvlf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2utcutawi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2mpoodgxs.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2asuuella.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2zsgslaiy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2weiqowgc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2uggmseep.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gt2rffjhjph.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2nczlmpzs.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gt2ukbnwuqa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2zyixdkmq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihgupika.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izxocwmt.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gt2vqygjvha.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2rstfjfdd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gt2yzhroxer.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2lkjbwvti.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2oeuxczst.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gt2yemdnmbd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gt2tjgbfgrd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2grgktxbe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gt2pgonkvoo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gt2lqseqmje.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gt2fgewxdlt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gt2nlfnmeeq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gt2guwbqfkb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gt2uxqbsaoy.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gt2yddryxbp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gt2jhwwezhu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2cdhezyry.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2tzajavfj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2aywugyfq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hstrggqo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2wcritjpd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2nivbppyj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2iodbhmcs.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gt2meqtfput.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gt2llpxglum.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gt2mbfbuctk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2slqmatyu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2wyfhyjwk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2ofutmtjq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2fgdkymdi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2tnehtmzi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2ewlbtwas.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gt2xhyjxemz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2hlrjjobm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsrbzrpw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2ekvsnack.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2wibhmodj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2oycpdnnx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucrbdrzl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2evknjjdz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2ejxrrdsd.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgmogahj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gt2dnlnqxoi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2wstltlar.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gt2ugvanmkj.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2altdtyui.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gt2wfywxnmp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2mfwzcwgx.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gt2eqgcvgks.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2klokbvuk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gt2juvynauh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbxyfoca.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rccbdwqz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhuinlow.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2dhigpqed.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2brtfjdax.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gt2drtxleec.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2qwpgrxpz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2ysjgupjy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2giindybp.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzyuqmph.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2yulotqzh.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2zctaobxk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2hybiogaw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2lqsvqjjp.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2rexsfgrr.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2ncsrxufh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gt2pbgarehv.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrqrhtz.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2cdanrcdd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwrahkui.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gt2fgcckblt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2utkrjhxp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxrdxhgj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2rvgttvli.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2gqsgbvmx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gt2lorihmgl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gt2obyldyvu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2rsmdignc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gt2cgchqnan.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2fmqmmnkj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqofqbkf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2xtstkycu.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzrpxdlb.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2bnszpcmq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaxkjdq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2nkkpzzgl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2okgbuuft.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gt2fpctgnyf.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2chvpeotj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2vyugscdk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvgnohif.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwpxpusg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gt2iyectoen.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gt2ccgdklse.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2ntgmbipf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhokrpvu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2fhtmefdx.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2fhnrhtmt.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gt2wzijdvhw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gt2nlzelbrr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2zwjipweo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2qqiurxxj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogrhvaxq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gt2oldsylfc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gt2pheyunjt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2rofdoncq.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gt2ikgdkkzc.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2idjbgfqk.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gt2ibgauykf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gt2exqbwnps.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gt2xfgzdszk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2vfghcrqd.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2yysbwjiu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gt2oivmygyi.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gt2qubekkun.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gt2ibessizu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2zhopqcus.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihijxoll.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gt2gudkjmmy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gt2mbsrgcgg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2zhwjsgjf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gt2ofxdwrhz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2smttuqbr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2wjqbrwqz.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gt2jfeqjxma.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2fnvsfzvz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gt2idojwsza.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prcxkywj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gt2mvcmccfv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gt2twdkbalp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gt2nrotrpkw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gt2axjupzqc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcphzjhj.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gt2xhltlctg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gt2eafgenwr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gt2miillkxb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kokzomay.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2zbcpzvxa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsjzyfpl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gt2qwxvccwr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gt2vyouzmsf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gt2tzzwphir.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttnszeph.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgzgbhff.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppyltswr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gt2zsjskqmm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2nhnnhxzj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2chcpyhvb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2vkhmnrty.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2mtdeglyo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2hzzjzuvb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2kkzbrzes.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpdpepjt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ozqxkykm.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxzymcrd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2xpsetryd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tinqwwie.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2rfefopaa.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2zsuaoxqu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gt2poeebkib.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gt2pqhrdlfk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gt2eezylizk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ywbusqfc.html


<!-- 参考信息 -->