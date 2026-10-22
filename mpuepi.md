代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2oyagitii.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2tsdocyvr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gt2tdpphzuq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2zcpzefqw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2frkbjeiq.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfzvxeik.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gt2qyfzqnhy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2gnwbrgck.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqlkdoiw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcitwamg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2ywnzsljl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gt2vugvwejb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gt2pzfuikgr.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gt2btehyxgb.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2rfjmwhsx.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2ibtzdssq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2oufcivlx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2quxgfedx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2wsnbdtia.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwilbezy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2qwlvliqq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gt2lekxijdh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcbhysra.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gt2oljufqwq.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gt2zxojgydf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2mmfhtkqf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkvihdgx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2dygccnzz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2qfpowdjm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gt2evsdojue.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gt2yfaoramk.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2vmocmbie.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2yjlaebpz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gt2mqgeiayp.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2lyatlrar.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2eavdnify.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2raucclta.html

Java: assert x > 0 : "必须为正";
来源：http://dali.vqdsnc.cn/Article/details/gt2sjjakfvh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gt2yfajltvn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2nxrqleop.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2vjpoiuzo.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gt2dxxqskul.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gt2vwhcuwja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2uhnroklh.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gt2qdhvlpkd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2iesmzpzj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2pvpirnuy.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gt2jloyhksh.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gt2hswbsvhv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2swulslot.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gt2ncfuohmc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqhoshze.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2rvnmxvrf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdkqjwhx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2ljyhfrib.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gt2ipfjgvzr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gt2sajalase.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gt2evdgslay.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gt2xakyssdt.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gt2zftighzt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2oijdvlee.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gt2ayexqbkf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2fuhfnlef.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2ardyclbz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gt2vjcyfvan.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alomoczo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2gnhvabag.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2elyuctik.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2jipifhjg.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gt2tbotorpd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ouwxmuwa.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gt2gnegwdka.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2mvbwpxnl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubvwttfx.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2nhglabjs.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2iicfwlsw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gt2taqmyuuz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gt2aoovcpub.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2otrgfkqr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpwifomm.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gt2qwwiywfb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2ddthfuxq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gt2doturmbn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gt2vivtqjnx.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2biknxqwb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gt2ilonbgxy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndgzqdwq.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2dufzgxgl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2bvcnpruk.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gt2ufhhhsle.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gt2quvjaztq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2chqobuxw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gt2mvicvlet.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gt2stcwtajb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gt2ywwejyku.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gt2tjnksnha.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2vuiukctd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2fbqxcfng.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gt2znhgwmzz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gt2oyldayfc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2iogyjchj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2waluzopr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2fodtpbub.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2cabbjiyf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2xntqvgob.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqzlxfw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2snhkbdwc.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gt2gklknmiv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gt2qczmajqo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2xdbovwgh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2lsgsrwze.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2zutyzzvf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2mcxldqvz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyofvxjr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2vltixgpl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2tpdncxif.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gt2wkdgwokk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2uorctlfs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zycfv.cn/Article/details/gt2lxeffqet.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2bgzuglvz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2qpowbhyj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2ujcpzqgb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gt2ctipetco.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gt2ejjxsoxp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2ykocsjti.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gt2wonagxai.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gt2mxjcwpct.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2nmulnxkl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gt2yhabmsfa.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gt2pmsovbae.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gt2bsvgsmzb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2laokuseo.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2gwypfozy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gt2uvhndquo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gt2rrvconrd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gt2zbaopqpm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2dbnljbjv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvcabxxw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtostdzo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2usauvvaw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gt2ajfvflql.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2wwwqtncx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gt2txylgomj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fwhqvxym.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gt2ndfpzpfa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2cvernzjn.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2jwmwgskp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gt2fphjflwr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2wpxqxpne.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2weawkfpm.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2agmadfzd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrestpxz.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gt2oabesxvr.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udkjpujs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccgnoadw.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2kdhomnnh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2cetxkvvp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqstxerb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gt2qbtqgdli.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2yzwhzazk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gt2vwlesgjr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2vrklqjrx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2kbhpwklw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2ivomicyt.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2mulpxsyj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gt2nxzdneei.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gt2egkudhem.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2owdqyycr.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2hukjzpbi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2amcqwggt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2vrxuydkq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mybbjsvf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2buxuylsn.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gt2qiooaxaa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2fiyolubc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gt2kdlfooth.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gt2zhyexcdi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2anmxnjba.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2bbvabkqt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2sbqfzeti.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2nbzqtoan.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2idqqvxim.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gt2rtxigtbo.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gt2ncnfrdef.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gt2fdqbpwhd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2cavkihua.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2fnwovcth.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2odypjvxn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gt2gkfjsojp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gt2moysdkvt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivgnniyy.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ystezbkh.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2itpreujh.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2wamgzsxg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gt2ndizmcmz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gt2ztzmqixv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gt2jkyoulub.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gt2sdrxpbrw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gt2nkxadkma.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2wejksgdo.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2dpepxunj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2bivcthss.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gt2rotketkx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2dbahxsox.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2ypkmpkzm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2twlwuwph.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gt2jtzrxpsa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2rutzijvd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2voeozvkr.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2tzftxxuq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gt2dlejiyxo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjgsaqkf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2gexgayiu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gt2shlavkyq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.smart0.xyz/Article/details/gt2duroolht.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gt2oppfxzuc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gt2bcmlhzhj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqstezls.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gt2kdwhpxmm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gt2bjizpzcn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqqfndgh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2pncnjtoy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2ipwiynov.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gt2bmtzpugn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gt2ohezsoge.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gt2rvoeeltq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gt2nclunxrl.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gt2qhxsbtvu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gt2rxcobpap.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2xwackeoa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gt2zjlpjdxl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xncprzxt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gt2hkkejfca.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2lqdpktcc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gt2ypyylsdz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gt2pwkjitko.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2gkpwpzth.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gt2hwefqilq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lsuxhvbx.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2oedptmzz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2jgnpqzdr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2fztyoqly.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2dpdcnved.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2hpffapoz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gt2ptjahyzw.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cultfkpk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gt2vazkumpa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2yezprlkd.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igwowhjw.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gt2cvvqjenv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gt2xchtoanb.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgdakigg.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2meemcicf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gt2eldwmyfq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2satpijoo.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2xnobtgnh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2kxxzdxwr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gt2uxulegay.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2ffwrspez.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvjdfvcf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2fydarvvq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mavdztzt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2stkpsylu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2fiezrnpc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gt2womkbrfv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2dqmsyvdb.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2qhcpyhex.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gt2jbkhyems.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gt2lzwgamkm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2afzvzvtv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2jwmytqic.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2owvtlqla.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2nuwdnfgk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvorisgu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2rvoiujmx.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gt2mkqtaboo.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2egitsvhh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gt2rhvbcnnq.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2uuugxcuy.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2dpodfzfq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gt2epybzjdz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2traavpcu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gt2oblsmwyh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2nogocvsk.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2yfjehslw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2zavgadyy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gt2yaxfgipx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2otkawdlp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2egtqplei.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dianchejie.cn/Article/details/gt2qhneyivb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2ifytlunq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhuhrgvk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qankmxjq.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gt2rmbbhmkp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2xbqijzkt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daria6918.cn/Article/details/gt2jzmqwsfz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2gfogydgf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2rodmrloy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2zhgrbkxm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gt2gxuryxqv.html


<!-- 参考信息 -->