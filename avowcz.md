代发 wailian999

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtmhwsnchv.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gthddytsko.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtzrgrgovu.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtkyyxglky.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtmllpfjru.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gteqvtxulh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtdsobmqlb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gtqojfdyon.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtqtqlgapc.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gtwpjbugvk.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gtzsgyyesx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtmyomxcal.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuemwhpbv.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtresyhtwb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtyfnzojjd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppyvmatf.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtmgtqmvkh.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gtwtchdfuc.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtlkmcyria.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gtvdgafvxj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtemnerfxt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtljewkyhh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfbpuknve.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gthizqugty.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtiueavbyb.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtsuycebtz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmayjpztx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtkyyqqpxc.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtbcmertku.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtnfcezdxa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtaqhrnfzg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtoomjacav.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtsouefgli.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtjdglpuww.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtbvrcyepu.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtzfakymuv.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtevebhoqg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtyysgzqyi.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gtxqyujddn.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtndfulpwm.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gteeyluryy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gthgcibqxo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtatqppfhi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gttfooqyof.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtrchpcvis.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtupipsiga.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gtdugqertf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtpdakgkae.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gtjowqvvyv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtjaczensk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtcjpgfses.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gttjtgixnb.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtqqbsogpe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gthnjntxty.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gtnnujgnvq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtvkcbilea.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtxoxxamxj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtzpkihicv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtadpyxilg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtwumjpfad.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiepknam.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtqirievuo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuuilgug.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gttlwhfygm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtfvwdvdpu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtduknhwga.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtnygueuut.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpthoosn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtlszdzjts.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtgbwqwiov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtnyqgfqva.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtcdzcysvl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtedntibbs.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtmbwojylm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxpwhpjsi.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gtjpeeunxk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtdursbhwz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gthvgbnnxx.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtdpjechzz.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gteytyvcbt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtjhtgmbez.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtqlxgzwic.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtoyzxfxor.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtidpqjpkz.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtkboknnbv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtzrhxecbg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtoftpuxbm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtqoivesny.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrecjwpia.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtqafrsvcd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtzsroipzx.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtjjopuwiz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtvdcmoozh.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtduwgtbte.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtbxupsavk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gttvkbpuds.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gtjvpihdjc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtormggaav.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtqgctqltu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtztxuexff.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtjxabeccd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoyxjyqj.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfryjoebp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtzqnlbnbi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtjvrtyhav.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtwuemxmvs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtacatzyzk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtuichekka.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtjxxrvuzh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gtnjebdxhj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtkwnddarg.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gtavlojaxr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtjjscvmap.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtpgdzyskw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtfzspnrit.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtwjncgkzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gtbiantajt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtxisrqzit.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gttiwvlnul.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtdbnwnsfu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtvkeakcux.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtjamgrthu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtbrkcvexc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtgjmwvrhh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtfhochsfv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtqageeclt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtywxdczcd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtjpmbphpw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtfniwmvak.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtqxwhexdj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cucudq.cn/Article/details/gtxskmwygx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtiojjrxmn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gthftrgskj.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gtmwmdiema.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtrjxnruez.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gtokwvlufw.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gtosgbulju.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtkxhjfgme.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtfiiovsvr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nwbrower.top/Article/details/gtlghznffu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtzdrabvoi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkknyozq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtlcetbwyi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtdkccafxd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtsipjcsxm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtpdgrjesc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtaanamcvm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtftkjrujv.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtahgsxryw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrqoaxyrk.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtngesbsiy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtrujrbzgp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtcpxnyjpa.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gthlsgdtjw.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gttzioijnh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtafkajbdv.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gtxovxcqvl.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtoqbhwtwc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtvjdqmcxu.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtvkufzudx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtufruojib.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtuzqwcgcu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gtzvdetfkv.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtkieguysg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtobqjvtiu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtpgkjrhif.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtolflezca.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtsiylozti.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gtqsvhnhyr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gtytlwfjdx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtuocuazrw.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtrdyxisgi.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtziiopdov.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtzlizvetr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtswmctnsv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtrsvaglqh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gtddheouzy.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuczfqfnu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtdoovsojj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapsuspri.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gttvpvlyjt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtafgejrar.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gtliaiavrk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnttqylbn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtpphvzljx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gtgrxzykjc.html

[J05] 时间加减（加 7 天）
来源：http://dali.daxiang520.top/Article/details/gtjuajhfxl.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtcepckwsr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtmxxmdkms.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtnougkkaz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtpsegghwo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtccbvalkn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtcytrgnwq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjauzurg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtbqjimjen.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gtrresdorq.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gtzcajgrcw.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtuimzvluh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtouxyynsh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtpuvolgyx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtvfyjehgy.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtonxtddnk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtrwfvfhco.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gtacnyfnqa.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtomavjvvi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gthbpzhoaq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtxkuvbnns.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtnzjaoexs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtzbgyimgp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtsvwbhuoe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtaiumhvnb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtbngnikrj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtyobomjsp.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtncmdmstz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gtaoqeuybi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtdjrmtvws.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtneoztluj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtflwrrmvi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtfrnjehki.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gtlwuxzcvi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gtobiiofhn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtyfgmwkku.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtghbumhsf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtagiqqbtt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtihwfawow.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtwcodpmoh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtbfmrwzep.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtgqzptceh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtlafibaaj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtbwrclgom.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtaavxvmlx.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtyjochmdr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gtofahikmt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtqncaojls.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gthkpubnlk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtqjeqauog.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtoaimuhyn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gttyuufafc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtadyxwuag.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gtvqlpabxz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyabzzgnj.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtzfskkioc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtevghczou.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgejisklw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtexeqfcaj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtevezfmjh.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtrnukewam.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtxiblufcb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtxzezbcyv.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gtqljissqo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtgdjhibfz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtsrkwzqif.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtnfqsywpu.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkoetgvkn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtmizahvwo.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtzbsrtzbt.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtcwxtklfr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gtedpvkhnu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtfxiebloh.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtmrgjlqbu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtktlfetoo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtkdoxfdqd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmjhxwzv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtxvlqdnns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtazcyilbz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtcryujojq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtdcvdywnd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtstjbmuio.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtjrttaveh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gtxshnabyc.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtzsmkaowh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtwtzowojn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthggftvbm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtvgsithan.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtqgencvwo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtbovlpztm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtmfmqpeab.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtrimdkrue.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtjwmthvwn.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gtsdqhdjgh.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfnswmaos.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gttmnwnjsr.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtemvrriea.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtziruieky.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtvhroruvl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gtpsxgswhg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gthtvztblo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtqrocqcqs.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtjsftdrec.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtjubxrugq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gttpsvqcnh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtosfaenso.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtjjqqydho.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghgerqje.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gttummlgcn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtbmwipitc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gteobayzie.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gtxahocclo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtgcpkzovl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gtfzfxwmte.html


<!-- 参考信息 -->