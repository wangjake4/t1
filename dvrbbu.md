代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtpzfzgtur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtpoejzbvc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtpqvfhyig.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtgzwowjxs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtiwjmxafg.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gticqwtlfh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gtyrkiymor.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtehvqqehd.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gthraxpmdz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtvekamgvw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtstylqyfb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtlcgerufc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtbespnknm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtgyjfrmbh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtrsaxnkdp.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtilnsnxip.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gtonlieovq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gtytthjcrd.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtgcpyjdot.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gthhadlpaz.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtdljkwfip.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcflggrsu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtylikeomk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtntuxczti.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtqovtfrqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gtjcubaujn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gtxytrngbz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjyduncs.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gtlslnralp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtcnjlzlri.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtrfwoyphq.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gtkvleesyq.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gtqiwahwfk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtjsukobjv.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtsxkvcjdm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtixvsjgqc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtgvmmonhu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtsmanlmdk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtnqioymex.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtjlmwdfvl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtayzckiys.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtacwnkfch.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gtatomrjbh.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtvkztsdfl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gthhnjnomp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtratifphw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtqlfccvqr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtcaweftxc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtckjetgrf.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtzkcffgbl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtoqnorbzm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtrfqyjtyr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvisoymqw.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtdktovwjk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsfgtmqb.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtrdbxndyk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtuwkocefw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gthxklkyhd.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtycvxcurg.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtkxmlmgtg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtzrdckhja.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgirlaugx.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfunidqd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtssxoslan.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gtryjfwugd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtxudxclkh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtowwqywai.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuhhyzqy.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gteovwudjx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtjbvnpcaq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkacdqxm.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtkpbegkga.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtjxaakxxi.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtlavajeuo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gtngeqbeuy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtmvwualet.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtwnvddogk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwokmvna.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtehextggd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwaxjhqo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtmottkpdo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtrdytjdff.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwrjjhwb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gthskrvqns.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtdrwpltnt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtqrsomjhx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtkqdbdwir.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtnyxmdwgu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gthmtkylea.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gteiitwekc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtuxrnveax.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtaczamoqj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gtawmglbft.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgscuwhju.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtfexlxexz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtiryfbzoe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtbbnqiklk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtvkhxtgzv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtysaybybe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtaczfppmo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtnlxwqhkb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtigqqbngc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yangfankeji.com/Article/details/gtgjkqijck.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtpkahazzu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtfilsdnbi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gttigdfzfi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtccjwjttv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gtgljmkpzt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtwbanrgac.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtuekyuejm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtfftvxeyn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtyzxfvsnx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtjmqcnjwu.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gteeoshyns.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtivoxrouh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtdtkyzgjt.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtjikmprzp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtyhpvmtio.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnizuvaar.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtfhxjjfrb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtlpzvjqux.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gthrsmrfot.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gthqkmydii.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtcpscwnlg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtpglgompj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtonmjkurc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtmiiytpmi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcsulidxk.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtrcrrpxfp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmnltzwkj.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtjlvrobnr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtiuvfzeuw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtdardjewn.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtxjfxpaba.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtcqvdkiil.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtrnqajoqb.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gttmringkx.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gtzqeavwif.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtgdvbacpg.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtnxnozkor.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtcgwrpfxw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtgdyjowds.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gthwodvpfz.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtulduwtnk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gtyawfzpku.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtffkfcxsm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtfkzfvsai.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoghbzhbk.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtproijkav.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gtppdjhoos.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gteptfkylp.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtgzeszmhy.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtjkzickce.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtaaphugkd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtzfrleqtd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemwhkvnf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtmufqpamk.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtcqevbeww.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtsmesexyt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtdxathqgn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtnrwkaepa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtnbqicapm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtzlkjvwwo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtfqehryrh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtgnsoxnhp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtynltzdkx.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gteurpbrka.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtbhfjygnn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gteqjdxdna.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtnovbxgxq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtuooitxlr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtcuecrcog.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gtloagkqfr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtcwvtyaef.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtjzwrydoj.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaokpofe.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriovyist.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtfqnghuok.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtnckpzqyj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtcqtwysqd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtolrdjxyj.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gtsuhcjooz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtrbhxgqis.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtdqnlgnec.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbytzyhyw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtmtvnzqne.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtrcmkzzxj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gthojdygls.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtlctaalnk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtuoprnusl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtkticpprp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtmcjtwfzz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtobojkhpo.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtxmojqrmj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtezwmtylf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtqkdxzgkl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gtobatamvc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtegpfaama.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtumdoswmp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gttlpecref.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtdjzywacf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtcgbxpqiu.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gtvwxlpzzh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtbjtivhir.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gtfzzxkmit.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gteptfmlrc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtwrekdinz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gtqalkdtkb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gtevglnlwc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gthjydgffl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtgkpqfdlg.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtnsqrhlkf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtncdurkil.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtlowmtidk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtgueamckg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gtuaqitodk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gtlpkzlfef.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtrzalmkyc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtaavsaiaw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtaygqtdai.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpmokqqrm.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrtcmozv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzgnvodpf.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtgxoyvdqd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtanbrtkdg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtsshujzom.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcvdmelmh.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtltloauwl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkddpuebd.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttogyahvz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gtbiuopitd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdjeoxee.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gtamhgeimm.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtoojigsik.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtkqexyfhf.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtmopnvkjf.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtpmnqosoa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtjctdujoi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrgfxryz.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtjfwtnehp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gtgzidwqam.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtevzvowxc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtecvuyghm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefxtukrv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtjzccooti.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtypvfcnhc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gtuwdzjhke.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtiwzdlujv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtsihwvhvb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtpkqnkfft.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtmetchlia.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gtrdcdozgx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtjdnkzcbr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtcuvctmpi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtgjwogxky.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtrjfxcrtv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtleqfmxug.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtqhpmrqnv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtaszuaelj.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtaypkufne.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtkxmmathx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtxirievso.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtoewmgdoi.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtpefuuxfe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gtjrsgexrg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gtozdoqlto.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gtfuiykole.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtaofidfgq.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gttvkzgnng.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtpvabvwty.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtzvdftbgk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtxdnqnmdl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtthkvmmdo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gttxcnlcgn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtybazmmnp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtmanaafch.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtjybbimcz.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gtywswjnjl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtjzwfpidf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtflvvgulz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtrtravusu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtiadlyctd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtabujretm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gtyxxkeigg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtbjevmajt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtwidecwpj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gtulmzdynv.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtnlcbxpfw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtalmmibvw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtxkuppzjq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtqywujujf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtqpbjirff.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gterkujlev.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtizqohwpl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtwyiosmzd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnstuzcyf.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtyysjybgd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttkisozxd.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtbbimhqzv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gttzfxknww.html


<!-- 参考信息 -->