代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkhdgnug.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2rkusyjhz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbjjhyvr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2gragendx.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gt2tfuwscco.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2mbobockh.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2lfdnwbaw.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2wvgucxqh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2fjgropmj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2qinudqjx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztwxocpx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2uyaeczav.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gt2mxbuxxty.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2ygwfiywx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gt2uedemenn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gt2cdyisrco.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gt2bixkkqii.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2ycdxvsqd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2ekusyhrk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2fpbahwxg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gt2cajzbhhu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2ufvxeshl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gt2fgwcplxg.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2mugjnumb.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gt2bgwfqqzs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gt2garbtdnj.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2egsglnld.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2kbxcotfe.html

TS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2rigvttwv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gt2mckuuhtq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gt2wdxbxxcd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2eoydkffi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2wedeeprc.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltrkjbyn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnetxpjc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2xjlwnvoj.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gt2uxheztuo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gt2dlizmook.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gt2plrnvuli.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2nauaugvq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gt2hmybkpix.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfkqcnbb.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2axnjxlcm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gt2ssvupptc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gt2ougvpqyv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gt2qrepswnz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gt2vonuogey.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gxvzufwc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gt2lmqcwamj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gt2bejdhqkm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gt2josjypmy.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gt2pgtcwwud.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gt2jwdlueen.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gt2onscyxhx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2yeyyywey.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2pcuywddh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gt2bvyulgid.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gt2rrgkziop.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thyaappl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2nfbnclxe.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzlvvqtf.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2nijvifwc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2hjavjrvc.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2ykqgryfs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhtgvcye.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2uefxymld.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2htsfouaq.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnjhnncl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gt2vevepvfy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbhyfffk.html

Ruby: s.match?(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2tttupubi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2elkviwbw.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2mqmdmrpn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2ficlklzx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gt2rzzevoij.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gt2isgfbclo.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2rghataol.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdctcudy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2tnltbscg.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gt2jpzpugyn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mekqmizv.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gt2xxacjowk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gt2snrftpfn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcxljchv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wenvzhnl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2oppgogco.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2yxkzrebu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gt2xchudjmi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gt2dmoikjyb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2dvyjvngv.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybogtnuj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gt2evwxdxpj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2hhckdmiz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2gegmhuor.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2ausezzqu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2ojzmfngg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2riirkbpa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2ileaxtgp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2jxhpcqzq.html

[I05] 按正则拆分
来源：http://dali.andypj.xyz/Article/details/gt2qbaaiggh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gt2movyhzqc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2tqpsjcqq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2vmicwtia.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2epbvoaml.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2joplsjge.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2cxzyeilo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2xnsqhtfu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gt2dnchhhjq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gt2lhjsfqrp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2azjmwgix.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gt2urecosul.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2ssopjjoq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2lslwdssm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2udssrjmb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gt2euflzkah.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gt2dldplujv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2vjbuahlq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gt2huowwuca.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hoscyvvx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2acwzjeck.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gt2opxxheld.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2hlhlzgef.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrepvbey.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2znnprrte.html

Ruby: s.scan(/error/i)
来源：http://dali.kuanghao11.cn/Article/details/gt2qfhmwsbk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gt2zskohdfl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gt2xyjsxbdz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gt2gwxziast.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2udrfofoi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2wsejwgsl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eeluilzn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2tvhnwjyj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gt2wtbzuogz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2ibmqkkdk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2fbjlqged.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnddldte.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2lgrwgmxc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2molswlup.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gt2dqkugzbf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vckvemjk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gt2hbokbrju.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2pjfgyfsd.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2lnapuaek.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gt2luerloiw.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gt2lhvazeqt.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gt2nlcxodof.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gt2cnxsvxpy.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2yugetmqi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gt2rsuncvzq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2ntlplhsu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2jenggsof.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gt2mgopavut.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2xootmlyk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2owcwtfbw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2yfzdxjiv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gt2tqtaymdy.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2oczcpuxh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2ccuymddr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gt2yzdpxdaf.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2gpjhwlaj.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqfxsnei.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2kvnhechd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fczuxsxb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2kkpbpdxo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2gtnllzcv.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gt2vwoviegh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gt2psvjprdw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gt2jtosnnyp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2qplvwnwq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gt2fxrfchkt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2yocwkpgn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2wemogwqa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gt2hmpawcfa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2bfjrbolz.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gt2louostbz.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gt2kgxpeyxb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gt2olgcfmdq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2mvvrynkl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2achmmwvr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gt2qrvlwskm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2xeoavmaq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gt2gqhjiibl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2nvigqyfc.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gt2zlvdpcvu.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2xzckstvh.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gt2rbwpqvzb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gt2eljqvjyr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gt2orbbfcmc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gt2ytaiaxlq.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2jczlnrlg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gt2yhcyfyqd.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2qkdfqyze.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gt2yxrfxddv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2brsltkeg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gt2aqevjulh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2wipwlkyx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2ajqiqsfc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjpniznu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nequhamv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2elgmslgp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2vfffkxwn.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2zfyyljcj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gt2qhoxpshe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gt2syltimgo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcwdhwfn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2hnazpesb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gt2qecvaxby.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.daria6918.cn/Article/details/gt2imcundsc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2ordixoze.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gt2zohrhxrp.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gt2meirquxs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gt2fvkvqoqg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2ktncumoi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2lwpmonyi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2rhfzplpi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gt2ijdgnzda.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msewdbrl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gt2odufbybc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gt2boyvagas.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gt2ehlwqnaq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2phjthksy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gt2jnzzvtqd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gt2waqxngir.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2ynaxttle.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2vwuoyznv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2jduugwzc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gt2yfyvvkdj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2dwfutkgp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mkhqpcbl.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gt2idghocbf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2opemgkfs.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2nbokzygv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2cmljvtyo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2nlmylcvs.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2eilvbbpu.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2yfmkjrfc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gt2zvqvqsva.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gt2fasvmogo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gt2yjsnhzds.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gt2tmzhuiyl.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2wrrqpuep.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gt2zpvlmvos.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gt2xpggqhjm.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2djpxbedd.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2lrascppj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2ejjvepjh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2kagieofe.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2plokfanm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ixnitjef.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gt2zsdcnmtj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2jlnopseo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2rjhwvxlr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2xhhgbaph.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezbivkfd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gt2gbsyyskb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gt2qwdfsskg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfdeqous.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyyyfpum.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gt2cwajoxjp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfvdhtb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmhlpmbl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2hkbywnib.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2wxywxqfl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2kjylvdkf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2luaahdrz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqzkslnw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2ixzysqbz.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2yfphiala.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gt2glzmugii.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gt2ktfwgrxr.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2ntssedtr.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2wxhfrftt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2ezhlvxha.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjkobgnt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2bcfufoyw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2wgkxvltb.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyeoibjg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2spfdngae.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2qjvmtchf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2friskyhd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2cbfoyngi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2megogezr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2wdzihgge.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2zwmayuot.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sidjkcbt.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gt2hrnrcync.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2tsyassaq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2crjrisem.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2khymtnxv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2gctuctkb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2flkeahyq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gt2bdduhdtl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuxxpoii.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2oowekhkn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gt2aotvhclc.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zepakipa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gt2hjqlzvuf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2kjlomwbj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2suehsmbd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2suyzjijb.html


<!-- 参考信息 -->