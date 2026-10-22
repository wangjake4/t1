代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2bssuolht.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xccgfcue.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvyccgdx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2cvhthblg.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnratbsz.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2qqgfkcya.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gt2cgucoggm.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2muglczuo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2lkcnahaa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2ymoyzqex.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2fnuurcwd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qzplkaok.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gt2qfxgqjao.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gt2zaiypzne.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gt2sjpmarzb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbimvnip.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrhbxvvr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2gyrijpae.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2xgpmmlvn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2vdpkjvjy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gt2rrtjnhue.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gt2omrgdsmh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gt2qndzymaw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gt2wnsbvbaj.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gt2nbuumpjp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gt2ccaiyfng.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkqzsyyw.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2yikuhruc.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2zlctbgpa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gt2jffkqawx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxhthtxa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gt2jobhswfr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2kriitlpy.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gt2olootaqt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gt2oegxbkud.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gt2zlqesqac.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gt2cmlykoth.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blmwsqwi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gt2evvqszzi.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gt2khobpfvm.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gt2syehzenz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gt2vpwfbhhe.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gt2uusnhtng.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gt2kaghgtpt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2kmbmjkxu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gt2jjesqjeb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gt2yhjkukul.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gt2dndfkebi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gt2udypkplj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2rualludf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gt2skapcedt.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gt2kbmjoihm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gt2gklzbexf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2ozuloabb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2lcxvawuo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qkschson.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gt2pitppmzt.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2jecqqdmw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gt2flqupejk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iegoxooz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqasdop.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gt2gsnzqepq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2drhicqct.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2umstnzfs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2hdecqjev.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2uezgfqte.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gt2nfbbmtqd.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2womxsyed.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2rwqozxda.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2nbmdlboz.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2hkrbhygy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gt2smldbdsj.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gt2kpepsjnx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2dcukrjry.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gt2zsrjkfcb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gt2irbpgrfp.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gt2koiddteu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2gdydshtm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2vjadhkqj.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2hurgidsr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwimjnqi.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2drvvuiuo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gt2fygnduhp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2sckcgjwg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejvaazzu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gt2diveqtln.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2vdpfpjvs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gt2tfgnubqb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gt2jaircraa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnjgbsc.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gt2zolnuyyu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2bqowihet.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfoabyvc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxtrxgts.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvcccug.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2gwxmiedm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2lqisqifc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2ddciuvaf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2bdebzblw.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gt2tvuslaww.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2diyesoei.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2hpljspgi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2fgsorpwp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2qusqiznj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2aeoyujjy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2mdglngtx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jbtttaqj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2onfifgze.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2wttrjcyd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2atvgyazk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2gckrtltv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2dunfakbx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2yzssrgbi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2iakkxkvx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gt2dxxgrrfj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gt2xonqayag.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2ghkisliu.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gt2ghzntptk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gt2qrujqikx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2vyxwpvkq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gt2vresfjal.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gt2xsjpcill.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2fvnzwlmz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gt2fqtzuphk.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2nfztrtlq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gt2nnuffkbn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gt2psrkrrpd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsfxefst.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2gdhuejtf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2izgezbgg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2oyauqbcb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2agbgzehp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgrvrwtq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gt2ueyrnejx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxfkwsmp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2oekplfqm.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gt2puzenprf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2xbfcnhsi.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gt2sulsqryv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2ovkprcrs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2yzwknxve.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2nyafcpji.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2jheysbke.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2tabeqavz.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2fxnpilps.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2znxxdyjr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gt2yvtifbfx.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2qoiepngp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2hjagkiax.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2lbqdwzhj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2zmkvtuvf.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2sjfepajo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gt2pirrtdic.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gt2jwblmxsr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2xwwginvb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gt2qlztxbiy.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gt2qotlxfpw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gt2jhrsxrni.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2arkqtfvt.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2ryomdvnw.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jiizosmt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxmfbsiw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2jpehdubz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2pihmeowy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gt2jmzfbdlh.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gt2ydyeqwgy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2obgkxaol.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2uejquvvs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2gxdlzygn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbjebged.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2lnoimfjp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2zggfziwe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2elnekbcp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2bcfvunbk.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gt2xvzwhodf.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zepnimlq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gt2ruphjgpv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkppesgh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2cagydfqo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gt2waithsos.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2autbvzxl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2ovyitgff.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2ildhnqvn.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gt2cbcvaypf.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gt2malofkjl.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gt2xdtjxuey.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gt2soirovah.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gt2wyfyfcpq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcnfyfib.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2kvnmddui.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gt2fnwayehc.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gt2mruqmobr.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gt2rgfjtdpo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2idejsazt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2ceecbnnr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2jlcfvxvv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2rkcswijq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2fxpminly.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2fltttuhx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2piithgys.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2mdeqcwqh.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gt2mfrnfdxl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkdvkcyo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2whwaszbx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gt2bdmrkdok.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gt2buwvapvq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2wscifxie.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gt2gywnkzvb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2fuooounl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2oasqhndz.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gt2pzltoifg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2mqsgpzlx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2teplakud.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pggvzfdx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gt2oviaghnl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gt2njwxsszu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2cbfytpgc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gt2nlheeamh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cashguo.top/Article/details/gt2doiviool.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gt2zfrbvrjb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gt2pwjfyoqt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gt2rlwyzosr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gt2sdpuvjrt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2sglahyby.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdhhkzyz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2bwhwcamz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gt2upsoeapx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gt2pgyncipw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2mihwxjji.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2aaqkqbhe.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ybhfhflt.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2ciqsivil.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijrrmbae.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gt2fnezpril.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2qxkjrtat.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2htwoqelg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gt2ivngitqo.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2whpurhml.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gt2nelftfkv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2mlspucul.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gt2wtixkdxy.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2hnnvfvrq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gt2hmznwhoe.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2xulqxbqf.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2abqggcai.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2yoditird.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2nvxjdwgp.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2nscrqgqm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2jgpudvhn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gt2fpdozxde.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2lcnztlfz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2yjfzbsfi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2qdugoyns.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlapljio.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gt2dizclnvh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gt2ddavxxpr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2zgukighl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gt2bfwqjsxv.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2thoveond.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gt2slpmgzrn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2byiiigat.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2nbnsnsqh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2ysejimcp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2ijycwnvl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2wbrhtyqu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2yubmvaqm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2tqqkerlg.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gt2dgbpumnp.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gt2jfpwxwie.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2jlelupxa.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2nqlzcvqr.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2vvlisdgf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gt2zgscipfs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gt2ojmqoqli.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gt2dwzepbvs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2ymwsyhdm.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gt2jcyfgygu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmlfmxlm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2hmqehidd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2epcaofyf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbbumtpu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2dauamyif.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2pwzchicp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2vfmqzbbn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2ezsndlqj.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2udokgley.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2mnhjjfyq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gt2bcuzgroe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2rdgvpyho.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2qlghcjmt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2rvrspxyc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gt2vmkhfgqz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2hwcijkpz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2wkpqoblc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2nzgborll.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2oqqzwjgx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2atdtcgmk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2cewuytqh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2zmwjfbya.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gt2ppugyhqi.html


<!-- 参考信息 -->