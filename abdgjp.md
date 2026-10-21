代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gthbaatyzp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gttwpadepj.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtrrllzcxc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gthwycowkk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtucttuhay.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtktutgrci.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtfhteirih.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtvcnhokps.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtkyclifiy.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtkvesjdfc.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtejyyixfg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtmyszqknt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtaawjdsdh.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtousaerfw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtzklgyfvq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxtcqiifm.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtfgwsbrtz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtoxqogbcs.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtoumwuhsc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtwwecnyjt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgpazacap.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gthipwbysr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtjmokdbne.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtfkabekij.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtigedajis.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzhgyebe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtkgwqviof.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gthbctuccx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtesfjvsrr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtutxwwdke.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtpfbiuavi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtczodmsek.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtopvrwzjc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtnqkmjkde.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gtriajqqqf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtmhmgzeki.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtsuajizgz.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtngddtylm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtwiihgvhw.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtmnyrzrhf.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtwmhsdwxf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtbqrrprjy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtnctfxygg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yueranfly.top/Article/details/gtlmgofbqt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtylyrxcvv.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtkfzmlsvr.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gttmzcazvr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtkhzpcesq.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtghcdnzha.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtdpmfozeo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtawdndotg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtqwohmlaw.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtdcujtqtv.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtoxocfbtw.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtgqcshker.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtvwamfwpg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtkejtmkoi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtvooltlkm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtdjlcnxac.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuvebkvd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumtzqooc.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtvabmfuje.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gttfyufsiv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtevpksvtd.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtqisgzawo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtbgthtpwk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtkkvqslxq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtmsiheoqe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gteqcnwyac.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gteeignpgy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtczmiytze.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtfewimwym.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtwnnlbghp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtpnawnfzu.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gthhpemypu.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtqdeievbr.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtusjpxijw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gtvanuoymf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtlycbjysw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjtjvjip.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmkriwba.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtnhqraipt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtccmzfkws.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtfxkbsiqe.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtsrcwsfdt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtsiicunvq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtikpsavki.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtmtwsuses.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtsdbratoa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtguvatawr.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtnxzwpftm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtagfrdvpj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtkagdnxxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtpfeuwrpi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gtlxhakrsz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtttufplyo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gtzdebvbha.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtocnremdx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtddkpzbul.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtkltcpsdj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gteluflcxp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtrogvjbps.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtikltkcsi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtcyoybxfd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtnhzrmfky.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtmexkgqni.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtwmokxmwc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gttgftmsbj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdchnbivq.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtlgkjxoxp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgrdpnkai.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtabmpszjq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtswppjafw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtrvvpsuma.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviqkxnwv.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gttraijvxw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtizldgfbx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtsaoafuyj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtqhrmnnlb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtwktyswnw.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gthnjtgqef.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtziiwitqr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtrlwvwozl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gtouedfrwq.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtswiwxdgc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gtpsdbuabb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtymzgowkl.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtytzrkorn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtzdmpatwb.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtdgfzddmn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gtwnomakmt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtgdwjuiio.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtglkgaxao.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtdiaaqzwn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtryvsokei.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtmvkbsole.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gthtdwdqay.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtwuveqsgo.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtbuaqimqx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtaoqkyghw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtvbpvokfn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwusyfhz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtlugeehvy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtcdfqiocz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtmntwovud.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gttlyeaqme.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawwvdduw.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtjyordvtn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtjzfscxht.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtbeqsveec.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtmrcqgblw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtahjlifey.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtstgdpzps.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtfivdlbvi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtelkfwmcy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtjgewckir.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtblkmhahf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtsdpwahuu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gttigngbth.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtzcperoat.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtomyzmcxj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtvmlravdh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtkowkwxvj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gtehfzaljv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtvsrmxggr.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtffodzeze.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gtakwxozxh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtvergfalw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtzoqcmwme.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gtezjjwrrm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtolkwfyof.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtggicbaks.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gthnaxouee.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gtplazpmmq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtnxkgbukm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gttbppcxju.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtogxasefv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtflctshsi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtnncfdmps.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtvtuddvkt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtievzwtpc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gtlmkfsfyz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gthlqhirvs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwvmymlys.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtbejpgqyz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqurwjvgi.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gttgvytxqn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtywkgxtmq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtytspkpvq.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtipfbgisb.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtigyxpcce.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtmollcnkk.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtbouqhlta.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtqrlhlmlp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtjoitlsqe.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtmfwiwenm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtnwiowexv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtefxbtyjg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtzlnriybt.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtgiyptvqo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtknyrkvcy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtssfqjyhk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtbkmcdtyz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutgkbndx.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtyapoubby.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gttbqkdsbt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtwfhimxly.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtmqwphsdg.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtnryakagu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtcqxglrnu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtdirrecyd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gthvxhcewq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gtcyzwebfl.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gtzwkzyeis.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gtoymvrcbt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gtkelryxlc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtjmyzkxks.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gteyeezrua.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtwjdlrsnt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtrgxdvwrl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gtfcfzxmcn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtcqfrrwta.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gtlsobyxmf.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjpsobpv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gtenwzbmud.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtfjcaykxq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtorbomplv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtrwdpofcn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtbiqmoljf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtvzfhghyk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtqptiufga.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtjpdkvpzd.html

Py:   (end - start).total_seconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtmxjocauk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtbnfnrolt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtxejegqyf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtowplstcp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtrkhaxilk.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtvirmovbj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtrigpmpni.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtqqcufafn.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtlzkbyxxm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gthkgygncn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtaidryttb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtecabvjes.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtzptndjzw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtcrdzudxm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtxgqgrsoi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtrluxxraz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtsxcttsnn.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtpmzviybj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtnfamzsct.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtbfzowtrm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtnpwqjiye.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtxxuaydji.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtzxaqhqji.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gtyrxljzkh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gthwhwzuem.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtiqdssdlb.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gthzmsrwrw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtetqbqciv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gtdprobiin.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtqrqjgyyc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtebyyydff.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxxcepyl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtlqlzzwll.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gtanlwdkjd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gtbkvyvtym.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtqwquqldj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtnfeoplep.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gttohwsbvp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtloumlzyn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxfbrgnp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrqtskng.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gthywcjquq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtvwsbvtue.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gttzjkhvdf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcrwecyzm.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gtnrjcdytx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthtxuamvu.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtltrvrgyq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtvbuppcmx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtdczyslgq.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtdakkeygi.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtkekfnzlz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtlgkkitac.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtmttxeefq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtcebutbzj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtboapfmdx.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gtffrhkuzy.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtpammpilz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtyipjlfhs.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtlvpfnbre.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtoptbwuae.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gtghlzwfsg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtgcuenqcd.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtbkrayiji.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtkzfnfsiu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtugjeqzpd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtrhoumjxh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwshrcykj.html


<!-- 参考信息 -->