代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gthxkaqxvv.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gturqxlnjp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtfarzjfur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtscgueszw.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtmdqoasjl.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gthvtcdhog.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtuyhyeywd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtchcsxnnh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtfboowudj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtoefyzogj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqcbrsij.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtnrlyobgn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gtvhkglnan.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtzmynmvga.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtiamcrlam.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtdajfpfkh.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtomdiijuj.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtvcndoxig.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtxljvkgga.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtnbokbxlt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtwwvjprhe.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtslvkhmqh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnougafl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gteggfdezv.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtlcmvvbru.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttkyiqzli.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtgpboxako.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtidjgfmcq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtfrpuqagv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtyiaxexnu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtrjmhzecp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtdssrrzps.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtslbzbvjo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtubwqyqpp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtzmoxsnaq.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtqeziytdv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtqwkuurlp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtbzkswsom.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtpipzjfza.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtovpdbqyv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtwoxeapmr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtgruabjow.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtbhkezdzq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtpdxwhxsi.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtqcbsgigw.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtfigjhubh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtudorxslb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtkxprelfq.html

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtbyqpvttn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtgtjllzhn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtpzabbded.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbauqsho.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtlmrcibjq.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtcsuxeqqz.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtoitqcyzt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtwpyimopi.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtgayihqmk.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtjarsylpo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkiultrl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtahhgiqrw.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gtehqiaygs.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuseuetdd.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtgqlgylol.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gtahyfulxv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtlsjsopgd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtdgyzvpqu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtmjllxxzk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gthdpcxyqa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtghdjphsn.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtgmzdupdt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtnthrzzjg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtwlqysaba.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtcarmufhx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtgwtfokqk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtoxsbunyr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtjdgdwbml.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtqugjfsum.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtuhjzonbz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtscytzywv.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtuvzprrio.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtxzkbtmid.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtuoidbtqc.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtulkkjcqn.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtaznhmltk.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtwhfozayk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtntlqfqdy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtclizvdbb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtbbympxqq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtgxzomovt.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtqfozkqef.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtueptmqro.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtynywtlgu.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gtxdmxmxoe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gtjoiuhrye.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtkdpkyyoa.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoohefrnv.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtrdgeujkd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtzowqdvsa.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtlzobkzip.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtjzxhnkwl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gtinxaatlj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gtjksseclu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gtfocndkqp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtgnlowpkt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtolmrwhvb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gtzndyholh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtixdfiimi.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gteikyauzq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtvnysoqoj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtlvlpoifr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtkotmhmjz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtktzupeil.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmapowsan.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gtslvsqmfm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtdqscxoph.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgjttuksd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnluzxyxa.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtbmoypmwv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtighgsaqm.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtbpvvcshz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtqacfmtbe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtewjmyrkm.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmxdddxjf.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gttxmkgxmz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtekuprngl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtvowtdywj.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtsrcjpsao.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtxxveymly.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtasfpmvhl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gttvuksohp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gtmvlkxsvv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtbfsuynpi.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gtgyjuitaq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtaydzziuj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtukxvvjwi.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtilqufybt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtjrvhmmch.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtoyutgueb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtrthkfifl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtolexhxhq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtvuwjpoqh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gtuyuacvkm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gtclxscury.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gteqgyqqlq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gtqiziabsl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtmippjvhj.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtmsyfazwb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmobxqsla.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtwqukwawm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtrjvsoqgc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrakjnak.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtitkexatn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeubjrbx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtiuothkzm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtqocbouat.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gturargssn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtlkbpdyml.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtppsdelvs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtnsmtuyaz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gttehuhnqp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtgwarmllu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtoygcnzur.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtlmczajfa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtgjjkewyw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtvjfgfffj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtfyluoorp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtakjbvpsa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gttcevtwwr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhyfjwnw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtezlopigo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gtsncipxpj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gtptlsccul.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtnzdulsjd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliyncocj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtmjixiwqz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtxtnqvaaa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtlfwmtyjg.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtzwryohqn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtbwtmkryh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gtvzfutxrh.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtppmegcto.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtnkcxkvzy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gttopsbebz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtxuyvszjl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtfkhrhzeu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gthbpkdvkj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtxpztyrdm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtfjhoiesq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtknznabbq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtjdnmigfz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtwirmxrom.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekqzgdkc.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtxdmfpkre.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzfkimssn.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gttwurosqu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gthpdaofrl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gthgudbxhq.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gthbwuimje.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtmxdsbgiv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtgnxzoxen.html

Go:   time.Now()
来源：http://dali.sufxvd.cn/Article/details/gtuwpdawhq.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtvldyhcrg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtywltaytj.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gtvlqkukul.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtdkklsncr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtktrrxoor.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtctnvbsbn.html

TS:   d.toISOString()
来源：http://dali.smart0.xyz/Article/details/gtjdmnbknv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtjxsfwxab.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtpdfbbzpb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrojqtjcp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gtsaembgqe.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gternhycab.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtoslhbskk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtkqbhybba.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtziprxkuj.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtmifvlinm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtnmsyqorh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtstzoccib.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtglexfeuz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcnzduoi.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguohktzs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gtuwhstrqx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtaaittuwc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtcedforru.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtbuorqaoh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gtvlsnxvoc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gttshpkuai.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtxejjumrg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtsatahsyt.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gtzqfposjm.html

Py:   now + timedelta(days=7)
来源：http://dali.vqdsnc.cn/Article/details/gtcefonfee.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gttrsiwehx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gthcxotjoy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gteupmztfq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtbhpmqfhn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtljxlmkrr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gthtsorrmb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtufujuifm.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtljltprei.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtceaprner.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gtktshohzc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gthngfgtfd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtxhqmjeac.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtfpnqoaii.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gtpnpvemxe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gtmwpdvqvw.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtbjynzuie.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipzpvmxv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtkjlorcvr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtycjhhkee.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtvdrvfabb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqqwkseb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtgpgmajwx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gtfdlsllgg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtgfbtuqgh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgctbcwvu.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtlystwspn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gtpkgwrjal.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenbzqbuy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtwmipzkrz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtyjdxjhyj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtzumyevnn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtsbmjuejb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtttgycirx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtfshzwaef.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtcmombikv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtjdnnyabo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtwthxcqof.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtirwpfyeo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtndkmrwof.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtdacddjit.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gtdbygbdzh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtkwkjgkyd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gtjhuxdkyu.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtxrfhsatp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gthigqzcqj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtqzgsvvjd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtarcmvptf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gtqecxzjbz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtevolmv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtxlfxrcpa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtumkjygvl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gttxrvlham.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthmenhehx.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtfovzyipo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcqovrmtd.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtcyxzqoen.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtoyifivgo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtnjspfkla.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtelbalcid.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtljjbuztq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtkqvvclxu.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtculdnngr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gtszztfudy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtgdjqdzvq.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gtwyjmvetu.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkyrztxa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtaznufjbx.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtmmktgldd.html


<!-- 参考信息 -->