代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2kvmuuxqq.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzbvhtfc.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gt2wbvrsomy.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2ubcigija.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2qsxebjrb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mldxigeb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2zkfsdkcy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gt2fsubdhbu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2rmrffxmn.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gt2ejsdbnui.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gt2cgppfwbo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gt2fgmcqcpd.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2idajkwsr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2pkpdoezh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2vlkvkqbh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2duqxtayd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2qauwifxv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gt2scucfcet.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2orrbkmkt.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2znqwvorv.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gt2xfjyvhtc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2egspmuqt.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwdabvqr.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2obsgacug.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2baapkcvy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gt2psxoutqx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spwjfswm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gt2zskwmqgz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2zgtctdew.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlrsvdth.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gt2ppqshgoi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2cwuwdaxz.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gt2pcbjmrxx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gt2ghnilkrm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gt2tzocmaun.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2pxvmjqkp.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gt2tsblgnsi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gt2sqhmdmou.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gt2qwpsitcp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gt2icipqobs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gt2kkorgtbx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gt2bsiucebx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gt2nozkuikb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gt2liztppkl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2sdaggczb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gt2mphkqwgw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gt2ppnzojko.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gt2vtagskpg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2eidldxhw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkizkdf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2vaknkxrr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2wpkmrqkx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgykjhqt.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gt2duvdrhlv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gt2pqdbqdrs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2vpiorpnf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2cnhdnlzz.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gt2yeswkxyg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2smeriogf.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gt2zfpmztnr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2grbyahkf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2uevymwwq.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2ucueqxca.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2tqgpohdq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2wtdacefl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2rqmandvd.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2gfmsvmbj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gt2lkorikha.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2rcsizpnv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxnwdqiy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2hwgmdjvg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuarbnfq.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fikhopxs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gt2mwsxvfmy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibtmmpeq.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2nmomsdtd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2otdbflzt.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2txesatgm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gt2kizlmnhc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2vpunjgcs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilkxrtxh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gt2gagldchq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gt2mklmolng.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gt2pgmaogfx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gt2llqdvoek.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gt2vyiigbkk.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gt2nclmfezt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gt2kamkzqvp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2xzjyjopo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkishdgj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqtxdele.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2yyblkhze.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2xdpzolso.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2qfjjbuef.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2shplrflx.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2dfajmfck.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2piztevmh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2lrilskfa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eddirwyo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2aytjutjd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2ohzrkwlz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2izttlgej.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2ohvrbdvx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gt2tqbtwenb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsruigme.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2bgkqhies.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gt2scgrbjfe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gt2cadfxrzk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2xwxhrszm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrbxouyb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbvytpwf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gt2xysuotvr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2nvubvkla.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gt2zodkhvyt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsnicjgb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2byrmgirw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gt2vodpaqjp.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gt2twhkhkip.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gt2nxzuqmnv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gt2clddfbqe.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2jjrbapom.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gt2jjudyvwk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gt2qigdganc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2qyeybiwf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gt2ztrhrilq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhwilhpk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2qmkelned.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2oaxzufed.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2jvbhellz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gt2btruxuvz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2jniloykf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2wgqfsfnr.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gt2hixqmpvq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2nfpgyvjv.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gt2xtpjijxl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2xzecoqkk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2tqzslcqw.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2peaxqjai.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2rmtvzaol.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2dyzrrokv.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gt2xgvjvtsc.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gt2rqewanuu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gt2drgoauhr.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2qwxrgpvc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2pcmpfdwq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlpvyykw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gt2fmkrzcmc.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypnlsjfz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gt2xzfqdqhj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gt2llbzbjpm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2litcoxet.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gt2tsgdgshs.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gt2zrfagqmh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gt2ujgxmxuf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2aadivfos.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2qjhijqpl.html

TS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2ydsceaoa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2fnsfkenr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2tkqdzzex.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcawrdds.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gt2frkojdny.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gt2jmnfxyud.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2izvjzssw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gt2qfhnqdhr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyyovjmu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2ynedgnuy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2axyjjuph.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gt2bcavdjky.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tswpukpp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2msubehuq.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2sxefiwtr.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjgcmlyn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gt2poonbalp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2moiasvop.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2eohefvef.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gt2ogcprizl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gt2zljodlup.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gt2ikldghcn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gt2xkgtjqmz.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gt2sncoiugt.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2iemssvau.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gt2ykkyvjrc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnbbejti.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gt2dtttaolj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gt2iwnqiznh.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2egcuoyop.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2zojphbhs.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gt2prklzalw.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2pykltklu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2durfkhiz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2kkubcmzy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2zdakqxjg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2stxzayip.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2ecjyujrp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2knqafcsn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2xdirqgbn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2dnxqcjlt.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhkcytbv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gt2llruqoay.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gt2dbilesvb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzgarkhs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gt2evkltzsm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gt2dqhlraaf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2aojyxxby.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2crqrccxt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gt2trqxxexa.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2jzkxqvxw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irskjxnp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gt2ofvyncbj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2weycnbuz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2omdnpkuf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2qpekuvup.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rapftknl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2xubxbqhz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gt2imrkqltr.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvolkzm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2fujimjsf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2nsyonfzr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gt2iiwgctmz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2nvohazbd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gt2khvkvcob.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2itjieomc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gt2fabvlmtu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2fjfzxhyn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2pginrwuo.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhzqlgey.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vnonqkhz.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqlhlvwe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2lffnsqge.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2ocoyoors.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gt2bkxkwcnf.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2qsayfxce.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuodmdis.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2cijlhaws.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gt2ugpnosqe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2mgfmngqs.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gt2wbhezdjh.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2ahwrcvhq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gt2bqgzrcyo.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdjzimip.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2kwswcrmm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2jkgpcgex.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2ucgjzddj.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2wkktpvaw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2uiakhzig.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gt2hxthuddc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lunqccad.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2ybuhecin.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2rvwzxfhy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ghvoyhfe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gt2szclmiia.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gt2hcslrvuk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2hvullnqc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2dmazsevp.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gt2xozyixgu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gt2ntxvyjir.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gt2irkhycov.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2qagvkacc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2tdyylroa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2quktuwtp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxsgauuq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2enlbqqus.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojbjdkha.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2xajgeyhk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnengeaf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gt2nfluhevt.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uojhgpeu.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udmdlwme.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2hkohzasa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gt2hixiihuk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gt2zdiwbzua.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gt2ekvkdlkf.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gt2ahfdnobj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2cmgzrvnd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gt2liibkfna.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2watctwsz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2xhynqugd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2kwekqmnx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2lytgkxde.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2rijbysar.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2umxnbzzd.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2hgaxpfzz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2fjoitymy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gt2ckaihmui.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2xlfxqovj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2behghgda.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2byswekug.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2slykkrgd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gt2sgpujavs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcxnkeax.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gt2polvgxqg.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2skuihruj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gt2mwxlvzpn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2kyfurdpm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2tmqglhvg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2xnyzatzf.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gt2fugnqphi.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2wydbyebz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2yjsmkdgj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ybartaqi.html


<!-- 参考信息 -->