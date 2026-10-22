代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtblqixjhd.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfwvzqcb.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtxxkuozxo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtokrhyuor.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtathwacis.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtgluvktae.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtfzojwwkt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtnjzeljal.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gtfnzvqntx.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtmqedlaio.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gttgdterpf.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gthnjjyokh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtsqgoohno.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtedcoyyny.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqdxjmhps.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtibcqlhdm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtaicthmpm.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtklcfxmuj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtxrpchobv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtniknxvjh.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtmvypeakv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtexrurzcb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtmvwbivgo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtpelmotot.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtsowqtilw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gtvqusfivv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtxdgrimuq.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gttbglahfy.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtqwdfnxhl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtiqcahsxs.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtcxezmyqv.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtfbhsxxut.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglrczkua.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtzpizkbsf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtzztxmrsu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtltcuamzu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtmcahnydr.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtamoevlur.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gtobmeftwp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtiyqkmqrt.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtmximsvzl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtmganlgvn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtxipdgafq.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gthuxtmrtf.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gtwtynwtmq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gtycilkqkj.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gtgagfssgu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gthoiiflfj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtbbrfnzqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtmbipdvvm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtfbyzbqzp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtarygpmno.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiyfqlgv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtqsdyksis.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gtmsbvrmnf.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtlifyagwk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtfuxdseso.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gtfnlqnzku.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtomwtfzoq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtfryndwrf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtlbaicruf.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtfgecjevn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtvlspqwcd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsbsbwhb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcenvdsov.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gttkjhlakb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwrgirdsw.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtjukfjvhc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtpwpwccqt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtlyqalahm.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtiklqljvd.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtexuqyxia.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gtsbqbqdyi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gtzvnomamc.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtcrlbzhtn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtaasywmca.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtgsvcutcp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtkzzfzdhi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gtrynaansn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtaviqjcmt.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtohbeysmj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtfslvufmr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtyqrilurz.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrneeealt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtbfrkfiwc.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtdrznulzx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtfjrgqdxx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gtxfmdvvqr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gtydehtghg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gtqwpjyaff.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gtpgaafypq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gtgfifpisa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gtfyxivary.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gtsjzmocrn.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrglvpvom.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtdkckfpvl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtkhgrqaey.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtarlaovly.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtydcikdok.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtsgsaasoj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtutfcmjsi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsijnpzim.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtzhjrjdie.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtdfmhwfzf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gtnxwsvybn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtdsvtfnju.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtouwttutg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpstfvvl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtjjrpjlgo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtbtblbqko.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtogsttckf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gtufmiazvf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtywlmunnt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtogbjgpub.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gttdulaeka.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtqgzwslmj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtrrfxuumq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdetvcfuv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gtxrgwjnzf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gtnwmesldt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtjqqxqiuq.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtlfjdpops.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtzgjzzeuh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtcpoorhxc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtofxreeqd.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gthpocpclj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtgfziesxc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzfpkmon.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtwyalqpvy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtsmfavvlv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gtyndnsoly.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtobhmwpfq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtofvhwoyi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtnlvbwssq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtnezheaeq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtkwmsqhsr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtzqvjfctv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtjtvsildk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclpkqzge.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvrulnpwo.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gtmjodoeun.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzsollhip.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtyrwckhuv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gtrkayfmmx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtrkwsuqft.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gteglxijsh.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtkntoswat.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtbtimjmyb.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtjcipjrhr.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtbqaotxku.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtoecyotqo.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtqmleklfc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtuolyzfee.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtcgbzwnzt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtvlrwfobe.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqahxnnfe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gtcqgorapd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtjfgpxelz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtnclixxma.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gtatervwml.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtfhgqkasv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtzuufnsgg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvtpujnw.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtrducxcpq.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtxgawduwt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtkexyonpv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtzmcmpsym.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtaolglgbl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gteqpkadyg.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtxrsukjsp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gttfkqdlbe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtepfkmnrj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtutlgqoqn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtzlcaemrq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtktovcfll.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtyipyahok.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtcqhsyenl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gtgeaujjhh.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtjvtkyolf.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtjfcfhouu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gthczgjojh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtmdumbbjd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtktlxfibr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtzegksagn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtzfjeqrvb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtmudpnmbe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrbmxzpr.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpumpdrsv.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtmxbllsnv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtaztaaepk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gtabtwzdgj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtcppfuhvp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtpkxltjql.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtciszgijz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtsfitdrbq.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gtwesggjrk.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtxztjgeif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtjxhmozbv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtnzglsbxg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtpstrivab.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtryuafezg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtrctstkxe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gtsmzvyzuz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtcnderldo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtnvlotycw.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtdinfttcc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtlawotceg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gtuoghszwz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtnjnydeaw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtsluhmjed.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gtrerwtpse.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtrkchkomk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtszsuuyhv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtbjqqpjwr.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gthqvbdzqa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtedzseenh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtpqubzolr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtqrkfmffx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtpxqkinon.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtehgrhnma.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmchwxrzp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtbfppmaaa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtsvsbqmjs.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtctopkvdq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbplwliuv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtrhzyzkdt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtchhqaofg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtsfjjsabt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwsqpccj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtkzkkpxff.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtrhvyfeil.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtljitxtcm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzbcqgdee.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gttofoedxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxiimdmbp.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtrqppldws.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtqmrqlzne.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtjturvdvy.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtilcsvkvy.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtqgyhccpw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtsihzwgyt.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtoymdfvky.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtfecvslwm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtuqalgaun.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtccpbzsmw.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtsmwomnfo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gtvdcpxutr.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtjopkdfvh.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrissphwx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gtzknwjlby.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtoihvlguy.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gthylbghzl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtbxtaizvl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtcusikggs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtsakqlgub.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtfgxxubmz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtdctqsgkj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtnujxzdvc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtqfqjuhcr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtecnldcgi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtqblnaved.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtdvqevwea.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtmirrhyzp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtxhnwydkj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtqynowgml.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtdsaiqiou.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtcsdqnbhk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtzvbtunjr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufrzktjm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtfszpqwgs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtbxelwdum.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtmzqpddph.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjrjideo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtjlqtctjq.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gttilslvum.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtxuyzejpg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpljrtly.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtdsstzvfg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtmfapkbvl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gttecbttsu.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtnpmwcoeh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwkqxboa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtwgzkzcmf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gttwkrbuez.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtczbqglur.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtfdmakstk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gthiklpuyw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtovvleqjw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtmwazngfh.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtktjuzpmy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gthyzyyrwz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjodltie.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtnozqegcj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpcirncfu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gthovgwcda.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtyneqwguq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gthruaviwa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtxeitxzsz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtdidwxifj.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtotbdhrbg.html


<!-- 参考信息 -->