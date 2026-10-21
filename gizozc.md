代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gteqyzhrdk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtkeohfnvv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtgemtqyeb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtmeyvqrsf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtgopqxxlo.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtvmwjqgjk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gtktfzehso.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtsmukdiqx.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtaimwjupz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtaxqhdejn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtuqrchthy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gthpipstal.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtbyslkfeh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtpoedxetd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxbnvbul.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtjccdtugf.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtzwrdxnev.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtkedkduoo.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtdcorlrpg.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtwsthdznm.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtksukvjzq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gtfkkvvyvf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gthksjmffq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gtpdwykkxz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtynuwhrxf.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvaguthc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtnlzrgsci.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtijutlctu.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtqzvikskq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gteancsxaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtpscglgnq.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtzxekcoem.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtpluffrcu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtsgxqkyfs.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtcouitocp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtnwgoehaq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbevbtyoj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtszpltttt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtsvruyecf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtgauxajmq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzogebrkm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gtitsnkvdf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtmmrmrymc.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtrumpnqkh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gteheqrrjv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtkqurjkxe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtvdtqooef.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtunjjmfzg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gttyuaonys.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtqufpwenm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gteevabcut.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtikfacdtb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttbglcmkn.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtvlafkfqe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkafvlnwd.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtojqypezg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtgxifgapi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtykgmhhfh.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtshofijus.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtjfcgqvll.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtqgmdqdpw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtezpkcjoy.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtovojowdg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtmjweziqn.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtrfsuwmez.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtfwbpdtzx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtajtrmkuk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtkacutony.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtgihlzspy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtulkdympe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtlukjjmrp.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtkevvyqos.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtciuctrto.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtuvxftzzk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtvvkbfscm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gtecdzezmc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gtovobiaqu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gthewatbrs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjabhbyg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoystuvmg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtlteyeyuv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gtrchleeht.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gtvnxqqyrw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtmdvoibhr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtahpiuijo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtcakgmsel.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafmlaekl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtoqmaulsb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtjnswbiew.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtolalqxlw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkibbvurv.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttyqdyys.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gttjtzhdrh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtcvxcrted.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtkkvpvtht.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtitvyccqg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtpyhzjkxf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtipcstabf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtkfiygzzw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtymvzumsm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gthsbtzcwy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtsgvcooqo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtykngqtmh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtpgtbtyhh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtvajugded.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtnnhvpvah.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gtbtyztdgy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtbmtraevy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtftuwggqn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtlhscodqu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gttozpaotb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtmipmagqv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtswnixoys.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtornpgjme.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gteasfjibm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gtycsxuqcf.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtfkwnsroc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtltnywqwk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtbjggldro.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gtiaxirzhf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtteejvzhf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtkywxjyov.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtfrwdqgmy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtlbkvdtuj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtgokwtmlc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gthohnerdc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtbcpiqefw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzlkkxrwo.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtaxviimme.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtauhlriym.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbunmtdh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtnwuvpsdz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtwwgxbxac.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtupcvmoxq.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtxkczjfbj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtcmspkpbl.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gthqphxddr.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtpvtpiuev.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gtvllwrpkb.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtrrsdvpex.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtkqhvkuae.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtvylqhtti.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gtyoagdduw.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gtcfhqyikp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtedqerxit.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gtrdhwkxhx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtesmiwnga.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtdeyrxczk.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gtklrclxgl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtsfldddrv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtvmtjqkes.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtbxpyufiu.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtqhnpjmww.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtwspxxepp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtjwtzoknk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtpbekzikz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtiibpxweb.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtbdqhxrod.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gtcxwglbdr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gtekhxfpya.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrhvldin.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtexozlmyo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gthbxktmqa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtczonpkxs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizcdywvx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtsehkgdke.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gthzfjziqj.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtecqvqnrq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtwczrkkjy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtrxtkwsae.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtlmsgirpq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtwcsbtrbn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gtopucapwc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtspfdnhkd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtaarctcau.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtqriivznd.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtjdpcoole.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtgamvozzw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtygqqabtt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtvryenstk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gttetfwbhu.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtpyaqqpuq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gttzhgkqaj.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtwjdmojub.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtbbvmjifx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtsutbrmxq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gtdfjddxsu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtymycfqex.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gttbbjxbcf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtvuzemvgb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtkwimllhd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gthkgnfaqj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtnghzlmyj.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtakmflzsk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gtbwxkumnf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtxsxywkcx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdynvpis.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtfktzlpis.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtmfpqwueo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtaujalqhn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtjtkalezl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtdbloihoo.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtmrrpxypq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwupauwoh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtzgouoyfo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gttgervtnf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtzcnusuaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtoprigceo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gtgrzonxpp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtylxbrrld.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncjanscq.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtsoyoctfn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtqvvxluos.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtcrnzrlgo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gtljifgwgg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gttigvitnr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcjrqegkr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtaguhjhvt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtzinkfioe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtpjdbiwyv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxvapcgli.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtxzxbufdl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjekeykju.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gtbnkigwgj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhhsdulc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gttivindkm.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtokqkxodb.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gttchxarru.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtmxgiyvlc.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gtkdritsoj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtnlvlidfz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtkgcspjub.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gtofzchhem.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtvqnhjlpm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gticxyqxor.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtohyagukq.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gthcvgijwl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtpkwgqrja.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtgfrpbvcr.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtfrriqddy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gtsogtaonr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtiguniblo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtmfjzaodb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtbhlzzday.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtagrxdhar.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtrdqrnzfp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gtxwyyqiyv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gtlmajzwpp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtqaxjnskc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtqfvxzjwe.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtvcfspqzr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjydnstou.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtphzafufc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtirvkyzqh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtizrnhjam.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtzlykkigg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gteqqlgmce.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtgzdkranv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtwyfpgmxz.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtnuwxfkgi.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnlitmzd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtsltlsjlc.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtmwtpldvr.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtgoftpuqo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gthznbggel.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtdlnkkeom.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gthxfspppr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gtjmuqfdpe.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gteooysmqv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtxaxdglgt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrswwjebo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtrzjdtcay.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtxttqkdso.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtuaxdqrke.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtsqdxjibh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtqtglpmfd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtkmdzkqah.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtydyosrqf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtegjgtcwt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtbordielv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtrmmrjprf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtnkakpcpk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtprfgigzb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gticrclibt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gttkgopgka.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtfigrmlhr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtwxbtfdte.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtvcqefeit.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gtyazhlzsd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtuumqjdea.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtbxwwxphi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtsxfpqvcf.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtnnsvlckc.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwojupoas.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtuydnleir.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxqcvxrmo.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gtkxtndrda.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpbbujpzm.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtgvdgwmqu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtphkhkifh.html


<!-- 参考信息 -->