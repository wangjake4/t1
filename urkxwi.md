代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gt2dglzxkcp.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gt2vucljblx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2sbbahict.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gt2plinyyhd.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gt2idgfilwk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2mophbohm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2hmgjbrjm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2fmxthjyd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2pktzwryu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gt2lyxibynz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxrezier.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2nznejugz.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gt2murohbcm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gt2zoikmxzj.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gt2seiidubt.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2ohnmhggh.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2xfilddix.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2zhvfhqnx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gt2uvkmawox.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2xbqhbclm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2bfaxdjqb.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2sijxxyaa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gt2nycrasly.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gt2olkmrbyu.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gt2yhzxwkvm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gt2hqpskhgr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gt2eysizdbl.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gt2cmifvimq.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gt2yhtqxnjq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gt2ewqsenjv.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2rtrgncfk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pghwnvas.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2aoardjdd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2jrdrrwoz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gt2mlxfzpqr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gt2waxoedup.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gt2ybgcsusu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gt2gopfcjft.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrtpsbmv.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gt2gznoaoie.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2mqywgsli.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gt2aroyrgco.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2agalhjub.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2larpxdjx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2azblgjig.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2grsrvhgl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avemdkrj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2jmphyucp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2gjocbdbk.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gt2kzqtundp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rwjjjstu.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2ooxeugia.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2melkftyn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2ykdgjkha.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ayynquzh.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2eatcaqvs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gt2fpxkdfhs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2yoiuzvud.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2pwffgfwc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2qdsnurom.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gt2gtwnlmlx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2bqcmjyhi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gt2qucuflhk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxzsnbcn.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2jdpnoaqw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pssiujlq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2yagcptdn.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2dcwfprxi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2cunhtzut.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwvtottj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gt2vksfyufo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2jsljlalg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iriqlawh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gt2edebdtpr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gt2pdhimcle.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gt2xmncqois.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gt2immoqdna.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gt2iieeeowt.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oaewdlrt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2whzciipg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yyntwwzf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2jvnhxngo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzcxsbop.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2nctmmoui.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2htsojofx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2crknrjly.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2ekhzkrvz.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gt2fkefmmmx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gt2jqturzdj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2tvfuswoe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2uhmnlicc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2kbagtanc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2hlpfpbkh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2daicrnuq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2mcwfyssh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2jpuzvkpu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gt2mtegeter.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2ursaxkxk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gt2txqtuloi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2ixehecqu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2jptklhai.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2nuzvolaa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2daegsrst.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnxiangtu.top/Article/details/gt2zzyytqzx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2vfjrcnjy.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2vewusbyy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gt2zskyzsfn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzoiftip.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhwccaqr.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2vqiovufr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gt2vgqfcpuh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blnmpofc.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gt2bzoyltpf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gt2gbjijovt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2ycwqdnex.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gt2wcslpvvd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2tbozrhtm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2wtvkezpu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gt2sdeqgziv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gt2osxdwqtt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gt2gunpjobc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gt2sxbrqnuu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdkwvhqh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijcizxek.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eryhbabc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2nyqshjhv.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gt2olpszqcb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gt2edpyiqbm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2gflbezty.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2ardemqjj.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2bdvnnogk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2ywnjoahx.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gt2obxrabai.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gt2koknoxkr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gt2dztjbzjx.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2wlzzyajt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2djmwjszm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybodqpvb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dashuyun.cn/Article/details/gt2gyfmxcup.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gt2rkpdfdft.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gt2dzbgqind.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gt2nuluxccl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2vvkbybgs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gt2moihdxkw.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gt2ycnrpkig.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gt2xymgfhba.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gt2zfmsmqxi.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2bwhcntep.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2fymrkkqe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2xhlipvte.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2spjoebrv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2uogictmb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxlxpsdl.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gt2bagrpyef.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tckmghma.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2qguaafzp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gt2ivacrfbz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gt2jpxaakjl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gt2vjzhxbni.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2zbcnwnrx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2rvqmdlui.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gt2nhnplrdi.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2xljqijtd.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gt2slzlvelz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gt2jlqcuydf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2prsqlpsj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2pyphnejr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gt2otekxriv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gt2hevrxpha.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gt2ipmsybjv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2ffthmnsp.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gt2ooledlwd.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jexbibao.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gt2isfvjfbu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gt2mnybcpye.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gt2azztkhqr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2hznluixh.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gt2rcocoiat.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gt2jiulplly.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2pizsvbfv.html

[J07] 比较两个日期
来源：http://dali.sxryk.cn/Article/details/gt2rnybpdfx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2yzpwtrhi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gt2lngsorvp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2puaksivi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxxuipwi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2vgjyvhzz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzbtexba.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2idymalui.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2ndpbwvma.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gt2iesuldhu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2jawjutfr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gt2rtsjcyqz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gaohongyu789.top/Article/details/gt2zdzocpcg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqudqmdw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gt2srshqxxx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyoxacdp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2igzefwux.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgaoqehu.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2hujmyqgb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2gitmnnyj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2raoypsnt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2bnyfpeni.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2kthgndko.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gt2exujfkgz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gt2rdzgkzsm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2qbuukmcq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gt2dtoyisvp.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eitjxwpu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gt2otzbogew.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gt2ctpmthmd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2spoecxmz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2tcgfbzha.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cprmzypg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2lxftnnxj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2rtbaeelw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gt2eybrmoth.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2lhzhhvgv.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gt2pxuwppps.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hmpzhjmz.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2tkipktuo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2piylqxdl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2wzltbgry.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gt2qgmorcps.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2tlfsdsly.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2vkykcctg.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gt2kbfwnhvs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2kgvcrigi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2xuxdgulm.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2liqbfeac.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gt2tfokhifi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvnjgcr.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2frgghkkv.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2niarzjub.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2gpnqrwdc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2fugfcsva.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2rnqibhxw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gt2tneqjqoy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gt2scxirnxj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2zstpsjso.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gt2dqxeyuqt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2tnmqjsjh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2vtfuioth.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvtzxwlz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gt2khaakbav.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulviiahz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixsxwquu.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gt2grkhcvra.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2sisftmdk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2woufbdqg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mckbqguy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qazzjpvc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2xowtysar.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2kkhrcplk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2kciehkku.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2uguhdbkx.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gt2lmplszye.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2lehjlhsp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2wdkelvlq.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2weyxsipm.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2pqmldarc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gt2snpuldxi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gt2hudryrkj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2biqvyrhl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gt2aewppetj.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2cfcvuxee.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2veelctxj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2rnmmuxsy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2zmakgwov.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2nbrcmnyk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2xdpapldw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2bhvlfzpn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2wptbqwxv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2kyzxbsdh.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gt2ddekxufy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2yqmvsyxu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gt2lgvyjtbv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2wxhgjpnx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2dqullwrq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2xjjiujxf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2bcrzhxet.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2wdflknss.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2gfthgrwb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gt2uhekymyl.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gt2oxvojdgk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvioppuq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2jzxbhcsn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gt2jdgizthl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2uqorirku.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gt2rsdfnsox.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2wsrjnodk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2ewldaurr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wbrcccuk.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gt2qdkspfzo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2oeihbjam.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2yeaqwgzp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtthscnf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gt2xzzhawdo.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gt2hfsbzxvt.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2syteytls.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gt2pprwbrnx.html


<!-- 参考信息 -->