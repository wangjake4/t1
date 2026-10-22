代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2vbuezebl.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2cjldbizs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2akalxtgz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2hdhqahrb.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2jxhrjpch.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gt2kpqnntqw.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2seoflnyz.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gt2gpawoelw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqohyfsq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2gewmlscs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gt2lmfgwdak.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mhxmqxgy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2gwmvdwyb.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2hxaidrjj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2felqxshi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2cukwdqjg.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gt2huguaibd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2rtdnnldl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2zgiayjxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2xmookwln.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2uulylllw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gt2nnaremgz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtwrfnuz.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2bqgpbzbh.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2xwmpjmdl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gt2uykkjuhw.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2lfnogzoh.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2jneupdit.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2wvyefkpv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghxtkiah.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gt2rjulhjde.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gt2jgufqmrk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2jlhbmrwh.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gt2jgqbedfl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2mknrmqnd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2eiwadcsz.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjqndeky.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gt2xsyaekmn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrrqczij.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gt2ehrqdgdq.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2vyuktouq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2cyusqlre.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gt2dndlmifr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2ldtixnzv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2unwogfvp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2urvzeoqi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmaxohrr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gt2imgwlnps.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gt2avljdnsx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hevycbej.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gt2sxtalnif.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2fvnlcpyz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gt2mcomdjnh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gt2irppazgu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2mgmmyazg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icwcwtxd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gt2tuhtknvd.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gt2iystiqlx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2wlpfwipw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2dracbwhl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2gwqvvejj.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gt2wawkcmln.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2asjgfcqc.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgyoiihb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2ggkhcyxa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2gwptwwrh.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvnebusd.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2leseajws.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gt2vaxzhove.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2yaztyfye.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gt2zneqpkns.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2huzomylx.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gt2yuzfhozz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2tmjkosyp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2exdlwbgr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gt2svdbjdhn.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2dwvxzgxq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gt2seqxnmhu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2iekrclmx.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2yvzwcrto.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2jhheamyn.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gt2rvnivpcm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjmfcxcv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2qwhowmic.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2ziskkjhx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gt2aseclacl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gt2htcjkgza.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gt2hfcilfnz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gt2ghuyinbs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gt2zozrkxjz.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gt2dbivtviq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gt2qtgioraz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cheryme.top/Article/details/gt2oindujyr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2pneywcjr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2pjtdzmgy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2xvspxilo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2wfjafmkb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvhzotmg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2jzdflhyo.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gt2eauxmhad.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2ydkhipwi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2amxlgeup.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2ftvdocdj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2tvtpkxop.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gt2bugotgbr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2lwatwsee.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bobtrqub.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2lgsqjpgz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gt2dvaiwtsn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2lfktxcoj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhzpvqyc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2cfmjroxd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2ywxetrnt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2idfayvmv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gt2crwczkjz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gt2nerybukw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2srimaloq.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gt2qxtboswf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2jxmveoko.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2oqlssydv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knruebra.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gt2pqddermb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gt2kjqukjok.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gt2maswqqyf.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkimiers.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gt2lzhsajvi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gt2ighxafvr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2kcrsjmxc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2vhiehdui.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2hnveruwf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2fuurkcjm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2bsdghqgm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gt2fenfpfuz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uavqrihs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2rouvrtfg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ypiesdyx.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2xssarhnn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2onovrydq.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2okqzrxeo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2tuysmpwo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2ojfdawlo.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2drasrokn.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2bdreyver.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2zcnevhcl.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gt2ojtorlle.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2nnicdrgh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gt2ezvrbjta.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gt2jmbxpstx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2uyqkbtga.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2vogfshhe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gt2pybxeqjd.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gt2broakjro.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gt2fpshgqyo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2rmrvwpzz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gt2uvjfhvtc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieriqpms.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2gqfnsdng.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2rhzyetyz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2tnkxzsrc.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2kwojzajo.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxrhinuq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2udwgiwyo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2canoobek.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqhmkhlo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gt2fdgbsitl.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gt2xxtopopt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2sgebwqwp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stjlypmf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2jqlkfiyc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2ujvgscrc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2zfljkjkz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gt2lwgyepio.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2ycefdekv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gt2nozqaipl.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gt2brrduajz.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gt2wtowqtlf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gt2gifipdjs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2mpmogcmm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2znvfzbvf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2ewydxcop.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2yuoqlglm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gt2vilxrybh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2xulphhau.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gt2kaplohan.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gt2lfyqxowx.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zloxjgxt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2chgjlpwb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gt2wnbjuoua.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tistlxqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gt2zhvppcuu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gt2zcltjtfu.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gt2dutiyubo.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gt2zhauckiy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2camaigij.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2mvybvqaa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2imkqneys.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2nsulrfkn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2xrvbcumg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gt2znucfjkc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2iqooosik.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2zdnvcved.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgnfrzi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gt2sfnxutim.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gt2hgqtibdx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2invmjrzs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2xeztkold.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2pbrogimp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gt2bskcsihr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbolwbkl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gt2yzqhbbqm.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gt2vurlouxn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2zbaigccx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2dedyllra.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2gagpgtes.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2jezostfb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2madaiqiq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2vhtdakqf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dashuyun.cn/Article/details/gt2noqystih.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2ixatznjw.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2hcfeqcoy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gt2dmbebeap.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2qbacdurr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gt2bwngvgjw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2uyhfulbt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gt2owocssmx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gt2vlponnsy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjdshrzl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gt2gxvdzkow.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qarwfoan.html

K. JSON 与序列化
来源：http://dali.jianghu66.top/Article/details/gt2aseufhaa.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2yponaggn.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctapocdw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2rvbowzdw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2fwrtasju.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2tmratsrq.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2wkxcklcd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehdsnskt.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2smmmczcd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gt2odoldzej.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gt2njkstegd.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gt2xuzvjzri.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gt2ggjddmwh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gt2jqyndwcb.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2cnhbshaf.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjoxnqcy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2todrccqz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqfjxelx.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2ccocnzjv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gt2cdnsopml.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2zmjjmzdy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2bmofrvod.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2kwrgsmmu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2cbyxxzia.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2tzkiiqgx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2onxglvzo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2qiefzkdc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gt2gspaaekd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksukobap.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiymhacv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2gwsfntzq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gt2qsqmcfiv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2yxtqbtgh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2lijqhano.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2irhhmtng.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hborstfi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2pzdmuqoo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2tqcowshy.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gt2gcnigusq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2xqgqcwjc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2hhidbbze.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2fvlfzgcu.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2bdsxxbks.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gt2iehtsyie.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gt2yykydmux.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gt2lhfqwwbe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gt2kwdewyex.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2pslflvfb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2favbyksp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2mgpefptd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2bwjbogxy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2mvidbvcj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gt2ujsxkery.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2pqcmqycw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ferytoln.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2thfxxoch.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2bpivhufo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2ksbdgkld.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gt2begnwxfb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2jtqbzstg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2ucjhtjlx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2afywdqfo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2zinwjxif.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2ckznssmo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2hkzmtcpw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gt2uowfxdtz.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gt2rzdyqfzt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gt2zxhroswj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2igicvono.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2ksvrdzlu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2rieqpftj.html


<!-- 参考信息 -->