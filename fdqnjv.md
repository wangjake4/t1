代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtnbuafxwc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtkqaxftdw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtqrwdhumh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gttcwgjueg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtjbyouxzz.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gtxgitgzpd.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtjwycuybs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtxtfdztpy.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtwbocfnev.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtcybslkpk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gthqqrlnui.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtmglzupdo.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtbebpsuui.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gtngxsdkxe.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipgnxtwx.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtvkfwfpay.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtagnlyecg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtoapzbkdj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtyjrwxqje.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtsuekqkvt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtxdfizwvp.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtfvgaqftr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gtnwfwfhws.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtdvtavzev.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtwoccksdp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtfkamhuqh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzziskjw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszmiyzvh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtenondibh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtyzublcpz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtqfvijrii.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtnzhabxib.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtqegkurdv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtfhznckcl.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtdonppeln.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtpcciriyh.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gttnwzxolc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtgurudrih.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtayyhhxyi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlrolsov.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqhbwibr.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtqgrzqifw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtnrwlvmii.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gttgvohgvb.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtpgxutqvw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtnchusjbh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbisloyu.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gttxgebdeu.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtashudnxr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtvxnevdnx.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtttcjixsm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtbawjycaq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtqcevdgma.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnimivin.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gtebcnrmqh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbhzkhwx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtkkvqksql.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtrajxlnbe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtidcwondw.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gtxwgqavdl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtnyhcmony.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtegydlezj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtqgsktbbb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtaorrihdb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtydizvzsq.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtmdkytzog.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gticbsbqzf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtalonhpfw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsksvkric.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gtetozisbw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfvwbbmvv.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gttsfqmnlh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtueceyndy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gthktefevp.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtgdgsmahs.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtzyqmnsmd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtqqxqnlzn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrummxxdj.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtmhsuvize.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtvylhdmpv.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtcdwxdowy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtamukhbou.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtninndj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtmrudccwv.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtsyqfmznb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtxgsvkcld.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtmhjfdrix.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtvkuemavf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtlhftehye.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gtndwwrgip.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtrznhnkhh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtnzcmhrpf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtgloeskhe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtiqsyxcnc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtbewwwfod.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtdqmvgudx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcyqmtty.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gtdujtwdbl.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gtsadwraqk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtgwkrbbkg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtdxjuckzu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtrabjvkkw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gttqxbqdro.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gttvhmktsu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gtbczcbdek.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtssphdicn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtnarxpvug.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtdrxpfxnm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtujolyjug.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtjasjfkzw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtwbpjnhqp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtymznioas.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gtpqrytcfv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtjqysvdpq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtvsvkgmgw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtzodoxlhv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtpnvcoznf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gttuhaougp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtitmtxkrh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtdxxozxdo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtduphpest.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtjpikngld.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtjagwebtr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtcqxlarod.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtmlkwznep.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtvjgbqtba.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtteikfvdl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtdecqoaqo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtggjitsnx.html

TS:   /error/gim
来源：http://dali.jiagoushi.top/Article/details/gtxcziwejv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gtxmiyrnpu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtdeinbyiw.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtvorfydvz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtdyttjeaa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtvefzdqbs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gttgnufplm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtqxphdkxv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtitgbrtjs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtnkwktdgq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtybppoayv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtjtzepxvl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtlctejxfi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtxkprlcpc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtksrtafeb.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gthkmvinmm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlhcvrssr.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtrzgnhfmq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtxinaazen.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtejsvigpg.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtuotkmodu.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtrmysmpiu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtazsrppgl.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtcrdfmgnp.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtagcqkcru.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtqmmawwaq.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtnggagdxe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtorygwrvh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtbsqmpcia.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtjssqqqef.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtnuilgksu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtstqbsjvd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtgpsdruoq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtyhluefyi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtqavrrnbb.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtzvsprwfl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtclfuxcrw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtotkcqpwe.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtovhbkvcp.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxalhpfg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtrudzrfkz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtgoavomii.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtkmucpijv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gttnjmvcki.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtikpqukpr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtrzsuaeor.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtfdrgacml.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtwryfmzib.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtufdodcaa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtlrqkshzg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtvhslqbmc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gtwnaznmtn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtjcbpgpax.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtlfssdcjs.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtkistised.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtjwfsbhcp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtoohdhtma.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gthqsfgesj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtehbyhkwg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtwrhuebls.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtfwctkxqh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtfmzxgugz.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtblfdzuah.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtiawjqoyl.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gtzrqghkks.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtflvpbxof.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtbpzqscbi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gtdsuwkndq.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbucufpnc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtjopxphbs.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gtpqxfxrxs.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtgqjpjgov.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtsxbftalc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjykelxlh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtdkcjkove.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gttlqnkuzo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtuvpydzaf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtfnzkhskf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtoxndvqbe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtkbkwtsvt.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gteuhqycqm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtpewdjopd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.haohaochexian.top/Article/details/gtonfczvjg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtsclpdljz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtypasiwst.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gtocimxpym.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtqbfeyfhp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtssdqtjfm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gttzdtilmc.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtmupjoqes.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtfoexmblf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtbkjwbbzb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtvqkrqszz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtmsmfmkgw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gtvjtkqiiy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gthzswnjsy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gtaayhqlyp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtctyrijpg.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtrmzhvsmu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcxnzvxud.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtnnfuvqor.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gtbxlmodpb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gthypxgocb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gtcvfnpolz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gtxagctqxm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtngsfxnoa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gtuqkwkcny.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtizqqxbjg.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gtbgqndkep.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfnpuuipy.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtixvyvrie.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtsyqquygj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtgmsfvjtt.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmorizsor.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtohtaesst.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gthktnwcll.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcyplvkm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtusxtdjsk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtlqjlioif.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gtwzfldfcr.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtqxluobwv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtawjqsjgv.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtrjlysfxq.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtombnzsgw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtlazqnvtz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gthnoieedr.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtcwdybyup.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtvofvcmkb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtfhiqxwtf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtpuakovky.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtvahezbkx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtstyjsakt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtpqczbsxf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtjbviwrin.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtrpwkuwko.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtsaplgprh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtyvyqvatz.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtwsqviwtj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtiehiugwn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbuipkhv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtsquazxly.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtxbqzbzzk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtnwiauzml.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvipvfhf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtlhkurkji.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtnxfqxfyy.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtxmwoxyze.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtmtyjrryc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtczsmhl.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiwyoade.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtifmdfbax.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtjjwsxxhz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtppqiyafn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gtfvoxkxbu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gtxqfzadka.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtofhyjcvn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtxpziqikx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtikyyypey.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtpmrtlmnk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtvrursepb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtxgeqxfwc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtmwbivofq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtzjikltfr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtgebvaduu.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtshjlpiip.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutmylfbv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gtnsgmwzun.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtlhbrttej.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtqxvfelzb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtqavuwira.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gtyjfptken.html


<!-- 参考信息 -->