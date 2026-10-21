代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtiwxteaxe.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtpikrvqhb.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtukrcokgg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtoidtywcn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtwlyqqbnf.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtnrukevth.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtnjbaxdej.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtprxyredk.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtnmhsgynj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnrxpxrwv.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gtujohrwyx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtgifltuph.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtrjugzlsf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtkwmmyrnh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtutxkgxbf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtnwhijgha.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtfmaievvf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtkiaazrwz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtuwhngsjl.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gtlaiumnjq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtwzhpedun.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtpbrrqpyi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gthnhskiiq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtjlawhnqp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtpygajapd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtekfncxjl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtrgcdijto.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtbbcjetys.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtpjaeyckq.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtyseozljp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaxqnyaa.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gthynqzeck.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtclbvuvdh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtzeezzozh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtspcuddwq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtbkmwiupd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtenwkdktx.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtuvwlxiks.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gthcywfaqg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtgeiwdarv.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtsjbvulfp.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvvljdqwz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtgprvcfed.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtvnjrmaei.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gtkzjuhtfy.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbhadnfmc.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtvadhfzni.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtfgiegioi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gtjyjbplcs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtbhhtleog.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnspeegst.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtxqlwnadr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtfrbofgwo.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gtcgvpicjq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtntcknlhq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gteeyewtaz.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtrfnhumwb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumksppvs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gthjqxcfty.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtgoifpzvo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtlmeoxyez.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtzwmxfkxm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtdpkwpecf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmcmmbyl.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtpkambpbw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtotqpbfjx.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcgrpgrs.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtkboxnczv.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gttjzkbvby.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtbfgjyesr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtwpgpybwy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtppyzeapg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtqizjieui.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtdndnxsmb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtqeerhpbk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gtwbvaiaej.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtqdnjmlqj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gtnbyhecjo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtylukbkfr.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtjjpljfqz.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtofivbpmd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtnackemos.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtdrquzzfk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtwgqdrqco.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtejadkhhu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtboafenjg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtudrplrps.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gtbadgdolh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gtpsmifqlb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gthlnddfzl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtwkripvov.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnuwaorv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtgrawjkem.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gtksbqsdcc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtfpewuwcs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gttnjglepb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gtstbzodgh.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtzdcunxmd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gtkeejjshc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtpivccycq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvdqrdair.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtutumfumq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtluxlgfoa.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gttkipowal.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtcilrijrb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtuiwqtchz.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtpljpkaya.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtummvjlkh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtfowdqfhp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gtaqzbnirv.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtqcohyktj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtsaedpolr.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtafcghhqw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtchdlaaaf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtacqrylwp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtrvwpvuhr.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gttamsppvm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gthhevmciy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtfhxrftrw.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtpdjadfuy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtrawbdgua.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtwkszpear.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtcciirhkb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtgonmwnpu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtmellrvnx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtedqtmgdo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gterfgzvyq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtqhwbufqe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtdrcjhjgi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtxgslrzwh.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtyhaipkdm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gtlltckxkh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtlzamcucb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtdrgwhaxh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtaxdudxvw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtuhhzvtkt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtjglrorka.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtqezknkbf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtbyfybdme.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtrfdmcyfd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtiypimpdz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtzefbiuva.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtefttgvll.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtxhggprpx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtleztebcu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtqyhfpgkb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtrwaovrcn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gtrvvbnzck.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtamxssmvy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtehahfzgp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtzwzuipgj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtboyfmqjz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gteyhfgayy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gttudpszac.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtdkbeqazs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtapxnaypb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gthkolsesx.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtzqsskoik.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtwsglqnvw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtkweynxfd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gtvujfttel.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtureqcexu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gtvrvlurpu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtiohwdhzj.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gthbhfubin.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtlnzkehen.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtgofeybdw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtudfinwlq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtihoekhhd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtefyezyns.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtrqoazjlk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtqzbcwrnm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtemiouzsr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gthfxuaufk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtbqcuznbt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgvisucps.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtdomqlsvj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtswnzuxes.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtsuwrneul.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtixlmrgni.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtxsminxlg.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytokiozg.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtgqnsonif.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtipcsscmr.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtkcvtuycu.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtbgwchsiy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtpksgfcal.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshfdupcv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtndpwvfkf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtrkokwbvd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gtgsjjtchd.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtkcpoygcd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtvzsxdlmt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtzncnkzco.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtsgzauwyv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtnqooyoui.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtiucmymfh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtppszecsb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtaeoafygm.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtyzyzkdga.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtgemomyre.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtkuxgjqca.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtdfiuzxtk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtcoidamvb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtfgfmtzop.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gthyaqsawq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtxztuhpjc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtmwecipoj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtcilpvmwh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtncfjgxam.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtgmkszswi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gtuqrhsqtj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtbdjyosyj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtpcmchmyk.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtejsgzfuw.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtbcuvafds.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawpdhpik.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtyymzvmdr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtrrfrqmtr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtfffvjwxt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyrulgjx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtuvrqxazj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gthjvnmnin.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtxdufvxvy.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtkgxgpnzk.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtnbiwllsj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtpbdaffry.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtukulbbmf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtgycrvgiu.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gtotyryzrm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtbhooxfdb.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtlfavohta.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gtbabagsfh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtwzxmntow.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtwusaiqdl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtlikdvokh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtjgavtzxw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtiulrpmbp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtarqllkrs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtrwmqdoep.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtxxsfpikp.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtdjxicvdv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtkcmsmnmq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gtgknvkdyf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtlaulykhc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtgovlhrto.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtofzspfva.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtxaomsvnd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtrnbivyjr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gtxsjqcbtk.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gtpizacjkm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtzhwsyeib.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtkhgrryqj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtykltzcuu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtkupaggnr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtbxxjmkhr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtbnllzjlc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtaipmodiy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtltoigyjc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtuulihfyi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtulsqeibm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtbeaoivjv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtetubrqqv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtokfnnmlb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtllbghaiy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvfuejqa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gteusipzuv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gtbucqklpy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttjsounlu.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtgpuicqxf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjzvexxjz.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqpqfkyzz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtrnisndtd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtpxwtztak.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtuopakavo.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gttijnppeo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtlusmvhoe.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtmkosgtxh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtjmsfotix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtzjqocfyg.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtkeeeqgjg.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtvydhtuea.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtngcffmbz.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gteszftptx.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gthafgvklb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtspmfwrvg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtvukovgfi.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtvlkstjuq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtogtrdwcg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtbakowsqu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtqsgynjwz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gthtvgopwu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtnbxoxgyy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtgkmtvkfo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gtfpjzhzyf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyphywfy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtocazmegl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtxlwkylez.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtvibagppf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoddbtgc.html


<!-- 参考信息 -->