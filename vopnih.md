代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtzxlitqpf.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtfyrlqhny.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gtwmpiovtd.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtulxtrrnh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtrujbcuic.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbyqdytvr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gttxtgpxfr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtdmardkph.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gtjimfgwuf.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtzqkoskdm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtmaxmvyrl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gtavyktlbo.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtktxujtrj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtnjqmpqcl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtwxwjzftt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtovajaisu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtrjsalcuz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtukgtpabd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtijpepbta.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtkfxcxqgu.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gthgwvexrt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtewoifkfe.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtqyvvgxkf.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtnwjmpeyd.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtzoxmnhne.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtqppxgrsq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzgdhxzq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtnogjloyg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtbxxmsbda.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtxiqyhnpr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtsbbuithf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtgzixfjnq.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtstbywmqk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtazzzgapp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtuirlntap.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtkyzkadln.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtfivawmaw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cqqwz.cn/Article/details/gtbatcmfbg.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gttwwhubgz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtdjfznrhb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtuspybdje.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtargozhwd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtqmcvucjp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtbkuqpfnq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtxqwlhyfm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtnvnnvvsm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtqupmzsod.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtqhewglfg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gtugvjbroa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtykfneozz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtbdbtbhit.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtntrfeaox.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtqnwejpea.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gtyytbzzng.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gtqquqopoz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtfhtmluqe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdywnuqjz.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gterarrkfr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvopnuflg.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtyskwfevs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtiagrdnwr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtcufocjkf.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlpgjres.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtmmrxxbys.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtbmkdddsb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gttuchscdf.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtvrcwsmaz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtvpvozygw.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtgapkfbhp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtqjsxvulb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtclmgyyte.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtwgirdpjc.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtatgqfubu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gtcadybbxs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtjdnwmkcu.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuewrvgtr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gttbxlxkfc.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtfgxiyxuc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtihsgjqbl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtaprmpjjp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtfialiiwm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gtaqqwfokz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtycuyoato.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtkabelsmz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gtsvoqujho.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gtplrupdwl.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtqmtdkxni.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtjawgyqbp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gthivhehjo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtvhntkvsi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtlnrmmkvx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtwuzxnjcs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gtbqzzhcfr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxrrsavb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtqvnwzedz.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciareavf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtiebjxlqk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtgxdxhqjv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtzamqsrtm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtqiowofki.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtnndowbua.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtdftszrcc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtahkncyky.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gteteszude.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtqprotuqh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtsapzqikq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtvjecddxw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtoxmpeaqq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtucrirrtz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtxbfoqbqb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gttsnbjglj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gttpgifvgh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtgocfibsm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhongyouzk.top/Article/details/gtorewjgzg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gtuqruobkx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtqfqlcnjo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gtrjjizvuz.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gtlanjyrhv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtbjxcilup.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtxocqnunl.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtutapaeqd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzigkjkwx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtusddmtqp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtybulygyc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtgvsftkdh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtpinedsqz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtjszdfslm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtvblbpogc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtojvkxtoo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gtixbmknpp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtaucihzse.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtplzikjvv.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtwnooaqax.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzrpmjiaf.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyprnwzn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtubslqklw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtwfxeawvy.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gturjycrou.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtqcpernpk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gtyalnjaoy.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtcfansciw.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtymzaecbt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gtxuxroksx.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtonnzgvah.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtadjvqtms.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtuntpkdhn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtsjbvkthm.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtfbfalkwm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtaeudptey.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtqbfcteqt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtvfiusnka.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxinvzxpx.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtqpxxjoft.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtkvwvvhiu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gttholrfvd.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtfntmrrnf.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtvrtxtvjn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtoswueahx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtneblxuoh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtpanexvvs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtivbemwuq.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtlkxmjxzy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtndrafzbc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtanzclyjb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtldrgfcqa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtkmufofcr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gttaeqpzpp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gthxnpppap.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtyoqtycar.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtajruqzqf.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtlhjnbxok.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtbfzzizib.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxcxzqlo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtanwoxhfi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtaexsppia.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbqinlxt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtnmqzclew.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtapdfdaez.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayavkldt.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gtheapeqta.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtabequaoi.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtccvcroam.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtzdhmmtfb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gtxqqauehp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gtrurqioxl.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtndasqegf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtvildwtnv.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtgrucuagc.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gthanpgbug.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtfyxzewxb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtllrdifzb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtobxhjukz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtlukyvxny.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtavfnxdqj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtcworxylz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtfnywvbvs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtlqmhcwlp.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtbwycxvoa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtxfisqhoy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtlfdmtkqr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtsbmlqhlt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbpyzjnz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtianljuuz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gtvqwvrdyr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtyqrcvonb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiohlbedx.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gtmpccorir.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtghaekiao.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtrbgufaqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtdussvbbf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrayzbtq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtijemqete.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gtdsvodszs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gtvxuehhxs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gtustttbip.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtmsjccprw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gtlxbgukjl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gtoutbjabm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gteygaxufn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtauadlxoy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvmvnyox.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gtxzruopgv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtdymxgtvl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtsgsmbcsz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgretpjwy.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtzngxoian.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtphaxujhz.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtlqsqmsrr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtnfmpnzud.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtwdpezshg.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtpguyhluw.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gthdmgobxo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjsumzzu.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtwuftkixg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gthsaferaw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtajeqdntq.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtcwfhkrfe.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gthfymdrav.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtaotcwebm.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtluimyrif.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtekalihdf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtvnrvjcxr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtcxbzufxt.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtutnjnofd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtgbsqyqkl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtlwazizwp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtybaljaov.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtvdnyxunu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtyfdopgba.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtpifqmjac.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviwickgp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gtgdchyclt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtefioqxez.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtafdcyarw.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtlhjiylna.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtauqtktuz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtzflcjsah.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtmbyylgdi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtfnfnuwpl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtrmeidstf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtaxgwpllp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtjooqnzwg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtezxvdvqg.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gtzyvyulov.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtuzemrcle.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gthrlajlvf.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gttwpkfhkm.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtrcouhogy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtidyvzugn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtzdwtbdhb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtuxaqddwb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtkhqtirvm.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtpjvurqac.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtrtoudqix.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtralevzcy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtffmdqbzh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gttltnagir.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtdvwhsqyd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnqpigbv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtnpcpqmny.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtgmxeryvp.html

[K07] 进制转换
来源：http://dali.dianchejie.cn/Article/details/gtuqropihw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtasdvapsn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtqlbhcwxb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtecdtqdbz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtbqqyplwn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtrrszqbqv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtyvnehmyk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtfzisgwyo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtulwahmmh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtfwzmgetd.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gttteohhvo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtgtggaidh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtdpwtmams.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtbygbcarc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtfqjrvlxm.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtngeaygvd.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtaljhilsp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtarxwpqje.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwehczbtm.html


<!-- 参考信息 -->