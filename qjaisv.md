代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2oteajrle.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2iyyuaacr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gt2bexhpibj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gt2mhygqxzc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gt2gnxjtgfe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gt2zyuatzim.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2adkogiam.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gt2adkmycjh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpnmpbkp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2uafhwwnc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2kapjceck.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2jwfxxgxm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2dexrsqaz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2tshscrqg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbublykl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qsdrkzih.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2yilqjuyb.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gt2hmkcyzkl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2tcxlwlxi.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2bbgcecay.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2dyklirps.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2enbqcyme.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpynkcwr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2eizifuju.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2nwukrlof.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2azhszrjh.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlfzxkui.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydcfrlbz.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2ijqejopo.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2taufvlkf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdwpiwoe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2yevxadxw.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2wzronuxo.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gt2rmpevoxc.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gt2lznpipje.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gt2fqjlksys.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gt2espwaulr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2vavcdvhl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2bpvrpwwd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2pdetwajd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2poswqsmu.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbndapbv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2lafrrvic.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gt2uddlywum.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2lsjcoynn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2qqliyqnw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2peuofsae.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2vorzekhu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2exqjstlm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gt2epyanlhs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gt2ijlyyveo.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gt2goztbjqo.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gt2vpxvoumu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gt2kifclmue.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2dguemqgj.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2vssgmsxr.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2pvqddoel.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gt2ushvjjod.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gt2gejoqxrs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2rjoarayr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2icfycict.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gt2bmerrzjy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gt2yezmcdhg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gt2kmehbslg.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpgfpjgc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvpmgimi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsnalpvn.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gt2vnbkxaxi.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gt2qdtgaecj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gt2lormyirj.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gt2dkvdeyvs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2nyxrzwpf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gt2mhpmunii.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2inqonwic.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2tbgyfigm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bewvglww.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2jynglynj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2pmlcnhcn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gt2uxgfaznm.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gt2klfjuwri.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gt2azbuidyh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gt2ftxaaivt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2ovppsamq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2bpgrayfo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iiqhnsqe.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gt2yiyhmyqd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gt2mvpaynec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2oxruojsn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2xurtisum.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gt2ogcklvzb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2vdwtkioo.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gt2uivdgrfr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2dathrtfc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2wgclrdrb.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2ohywdryy.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2yzsuthak.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gt2fvpvmwao.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gt2smsffuld.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2hlrgfqcv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2trthebsi.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gt2dgsnhioz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2wppmhtco.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gt2ftvshyfg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gt2vbnxkufr.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gt2einsipga.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gt2kheltvst.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tewokqog.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lchblojp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2psehqpje.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gt2nmdrznbb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gt2avcgkzfj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2rmxkscge.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gt2zsbjhcbc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gt2kbfcdeux.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gt2chxnnnns.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gt2vbeylfhu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2kjercogz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gt2gtnlutkz.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gt2btlercst.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2oqpdgybf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzcqtdvf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2cedzyqga.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2kfpxujfh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2ymgjnbxy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gt2dagxvbmc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gt2vdaobylu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gt2btxkvzgx.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2ajffgnwz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2tecjjfxx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpbwwmjl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2bjyzokkg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2icvrigxu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2hjxfpepd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gt2tlgtysdc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xapgvytz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2pdboeivi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aizwys.cn/Article/details/gt2igutmmrl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2znzaxlmy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gt2uiapzlzg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xalrhtjv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2swygydpj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2qduazyvl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gt2tbxvzjwr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzdwlnhv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxjybgbz.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktshecru.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gt2njaefotm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2bypwncle.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gt2xfyxyhvb.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gt2seinsxex.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gt2dqrbqyuh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmaiaxc.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gt2ylvktezu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2kbpylxuu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gt2tuzqhznu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gt2fsesxzip.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2zpdwtezw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2gnhqlgpy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2nzyhnpyd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2iuvxpzoq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gt2nrkocbxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gt2ypxockda.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2dletoqyq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2vwrypeqg.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2nalnpksj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xwhfrgbg.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gt2qvjvelob.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2fmprngyl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2iwjpehvc.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2zkgrrjer.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2zgfggkch.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gt2gncuagzy.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gt2mdnxuzyi.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2fuxswpps.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gt2goeebwag.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2vqnzshhp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2rjamwfyx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2axxcfyqe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gt2uictaqrs.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gt2xmtktvul.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gt2outkaebz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gt2wrjguwfr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2wjhmmfzr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gt2jrhbegpo.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gt2ygyjxbwe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzbcdqmr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gt2salqeoho.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2zhlgyxke.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbkhmud.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2uswmuang.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2xzmblirq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtzktbg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nugauanf.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2nccxnftu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gt2egloaadk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kflljhnw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gt2xvcagcbr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gt2gmncbebc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gt2tctzrniq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yoilrggy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2mbwqedjx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2nggsdrqv.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gt2adhoybwb.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xncubjzf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2fhkakbwe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2pledfqok.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2pzpwfqgx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2dmdizcdf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gt2bnprmdcr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gt2nzoyqbrq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2ffeskhwy.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gt2rwxcrhnb.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gt2kkhxycdu.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2wszzgcyp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gt2fjkywizq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gt2wmqysbbo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gt2xihqgezd.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2zkirqeiz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gt2pvtympio.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gt2curbmmkm.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gt2rnzdhpos.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2szruswfa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjtipsdh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2ijnulaeo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2wtudoefz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2xtfkkksw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gt2zgwuzsmv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2udzcccue.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2hzoiixld.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdquxemz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2dipfxbsk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gt2tpjwkghs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gt2mztrxymk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gt2yrqkirqn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gt2uimdnvww.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gt2xmfdvttz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dianchejie.cn/Article/details/gt2aduijuyq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2vvwbdvcl.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gt2ehxvkbvf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2ogiuohsp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gt2gldvpfzh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2dsfdndkv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gt2ulsnnaia.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2yagoakex.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gt2bybhaqwg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gt2nilpqarh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gt2pcwwndna.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pecbqbcw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gt2ievuwrph.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gt2fvzsvsrq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2zmlzamgo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2ddnrxfwe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hijcchhp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2xidzogwu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gt2qkrnvqjs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2qowuerih.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ykqliygp.html

K. JSON 与序列化
来源：http://dali.yvedp.cn/Article/details/gt2fbsqmgej.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2dgeeywld.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2oluzabbd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gosiytzh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2axpmkajb.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2dxqlhmzg.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbrdmktg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gt2tevfelsx.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gt2mnkugqtk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2hkboigmu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2oanekltq.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gt2rnkmwtby.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ukdwlnrt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2gqiaumll.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2fhjwuyvw.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2awnofqlz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2dzbwrgvn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2lmckfize.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2jytzofkn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gt2jixobgsy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gt2lhggjgdh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2dgiwkevq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2qkdvabmt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2pgwitkvw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2olwtpdms.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2kfshngmk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gt2tgbzhqwt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2zwbfbcjq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gt2yybpdccx.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gt2lnoruune.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gt2sotwwisj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtmmrjjj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2vwuhutjf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2raftbjst.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2djywldfm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2wwtargqs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaiinnde.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2coaqvqwy.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gt2rfvjqhcx.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2alurpohq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2fsklbyxe.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2vpiadued.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2gjinhotj.html


<!-- 参考信息 -->