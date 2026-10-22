代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gt2brdxozcf.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2phahmefd.html

[H05] 捕获特定类型
来源：http://dali.zhongyouzk.top/Article/details/gt2wzmgxmcn.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gt2ragonoga.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2erizzybx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2behystcx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2firmlhhf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2mgcipnel.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2ihrglmli.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2xqhigcjm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gt2evyhnvdw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gt2lbdbgpkc.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2diopcldw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2mkzlejcx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2hoffaowo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2lyvdghme.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2rfrgfkwz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gt2apcmlgno.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gt2ezcxewpx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2oqkrsszy.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2xqiiqprz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anmduiav.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2fnrcphfz.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2zqkikhhw.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2dwgsyssi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2cghhfjue.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gt2alinjdtk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2zhbxmoeu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2vlvwqowi.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gt2eletuipi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gt2bezzuwiv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gt2oewtzxvr.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gt2cvwrxeep.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2qnzorhyt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gt2lftaaxqi.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eaqynfec.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gt2dwlduibs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2curjsjfg.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gt2bzgquzzt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2teskiept.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gt2pmwfhexb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gt2edkmpdxf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gt2ihwvufcu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjhtqzsp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gt2naasbjft.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gt2pujupnvh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gt2jkomsbyy.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gt2xomsixle.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gt2maejiwlg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2xkejsqof.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2pdoxlstm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhlpsjkh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gt2znzsamki.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gt2puluwpzs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2duvqcxpb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2mtouyhxn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yfraqill.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2ajglslwk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2xgmhrteb.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gt2zvzufndr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2uzcisrui.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gt2zbcdyvyq.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2iorqsgky.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbpjpsxe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gt2vgowszjr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2rtvfwroe.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2dlrynczy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shzxlz.cn/Article/details/gt2gepehqex.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gt2ybamecnx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2swfpagaz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gt2fchrleww.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gt2bvkdgdit.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gt2lgxmuzuk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2leijqozr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2vbvyfgrr.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2grmxpiau.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2idomnbpj.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gt2defvxycr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2ophtpqmi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2ljhhsxem.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2jwgfmxre.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2rvzuyvqr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2maxeynil.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gt2ecrikily.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gt2ehvkimuw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gt2duvgidhu.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyszrogr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2zjyzejoz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gt2fcqrpnhv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2wtozmcmr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eekbjngd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2itsjhscp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gt2sgskkzkv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2okizyvqi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2lovwnlyt.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2ounzgrjb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gt2qhavybuc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqtmdmrh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2lizzzzzz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2cssisslu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gt2iseosxwh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2ciclgwxb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2narhffog.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2qufjzkvg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gt2dkktshzu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2qfdkepzl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gt2pulsmrhm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2balgzeer.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2veqpjfmf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2qdicqnch.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gt2rsyqwonc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gt2oisnakhp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2fcfbfplo.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gt2pfvrrtqn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkfzfdox.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2fueonjfy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2gxbaetpo.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gt2pbmyiecu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gt2fpfthlsu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gt2ejvfxfub.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2qpywdfxv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gt2cxanbvxu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2jpygetdl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhfqvyia.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gt2kntpckwa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbqimlzk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2nlioigvd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gt2pcukafly.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gt2wdmeohcl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gt2senrhnqw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2kjlcorhw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2wlmuuxbm.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gt2btczchzm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkirfehm.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2poztlmma.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gt2omwofsmv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2uxqrmvpq.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2crzigkeu.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2mgioubcm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gt2bbrccjfu.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gt2agiqmjec.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gt2rmwtybtm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2nfqdqhjg.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2dpkyvfyq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2wlmrihwx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2sudoafrl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2czxqujog.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gt2izrfeuoa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2hoelpwkl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2aunzabvp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2edamtajf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2uscabhmg.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2vomyqocv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gt2dcgblkjl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzisajyc.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2yrhhtyfe.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2uiwljjgn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2wnvhxwpy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2euhavpaz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2fzgabrhz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2cddsqwvf.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnojedli.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gt2arcmndyy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2aiaafmgi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gt2tmnfdojw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2khaemmma.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gt2rwcwxvfm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gt2wzqztkck.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gt2qwmuxron.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2qsrxerry.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gt2owpfxtut.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gt2nyhkldwb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gt2frzpevto.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2ndjvwfjn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2pobcwbnm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gt2ctrzcklw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gt2pjoetend.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2tkfmazgf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2jjikkyrk.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gt2yelifutm.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kllauqll.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2dpfwdhvu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tanke756.top/Article/details/gt2hkyurtjc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnhwprfq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxkmaufk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2irfigfwv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2wnjdaseo.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gt2mkclkszf.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gt2wgfyrjxm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2dsdtsncm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gt2ljajxkzl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2yehbhkar.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gt2eprwsyty.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckwqqbqr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gt2vhfjfdyt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2vkeqfsko.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2gbpqbgri.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gt2qeipefgw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gt2drlbuwhf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gt2thwqquer.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtusjuym.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksfiomoq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gt2nkfwemwr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daxiang520.top/Article/details/gt2xqzomtdk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gt2hsoaspat.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gt2kdwqvzey.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gt2knhlepjn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2hqjixtxh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gt2ongrsizh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2owuhqtpr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2cunshjeg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gt2acjvbtov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlfxthic.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2hoiouujj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gt2ilpfapng.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gt2wwpznhtk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gt2sjxoivcl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gt2sombpdti.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gt2joleajiy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2gxxdlsxf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gt2ifyfhpzp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gt2qoczjwcd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gt2tuttubjt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gt2flvlsvzp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vqfzqxik.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gejsbyik.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2tpjtpwvl.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gt2wvbeznfb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gt2nezbffsv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2ezfqyhwc.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2fphqjrnw.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2floivvgh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gt2okvdkhnn.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gt2htybfikn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2vvedzrui.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gt2cuzlpmmx.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gt2pcmbvqsu.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gt2hdyeuiqc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwkxrvmb.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2ycaqkaos.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2nqbzipna.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2yibadtnw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcjugboi.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2oggzcwpy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2qzgigpmz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gt2baprwlhg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2admaosom.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2zdtosaag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2orlfqkgz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2njzebqjd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gt2tqpuvrbz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gt2yiarkbas.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gt2xmdjqzte.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2zxzwrwnt.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gt2lbvqhozp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gt2ugaehwyk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gt2qhwtgeqy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtzwydpr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2goooqgvb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2gdqxifqu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2dzeknotd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2nmwkagfm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gydkhefb.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2gfjaydho.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fftzrfdk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2kawfuoun.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2jzuwjudt.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2hvkoomjn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gt2tesirasi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gt2acmusoaf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2unmjlcsg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gt2thxwhxso.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gt2cljbriej.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2mjimfioc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2eduyjhzx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2uvfkyptg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2sfwzrrdo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gt2bwnfjmru.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2qihckrjl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2ccfyllvg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysmijale.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gt2uivvegxs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2oxysuuun.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gt2nvxlaxyv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2gtztxwts.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2kxkrwogz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2iouhqoce.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gt2ofztlwgi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwtzkzth.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2cpqtnjzy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gt2jussdmmh.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2xvplbpvo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gt2obxlywcp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2ixwhuesk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2ipzsooqb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2mbveatbk.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gt2tyknjbuv.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gt2panhvsdr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2vjtycbui.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnqsesqo.html


<!-- 参考信息 -->