代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtgpxpmxqm.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gttjbjojtf.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gthdonhjjt.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtzlfxcrop.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtoaxeskbt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtzzyljmoy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtckykzprv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfdcghmhz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtaypfbstj.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtbuyxiiaj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtewtzvyhj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtfhmehbft.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gtaqkyvdsr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtltpcscsr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtmtywpmsq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtwieourws.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtvrevpuzz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtyyqmjmwu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtztqxhmlu.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtpuxwvhck.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtfyhtjcas.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtsoatbmvw.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtymqawlft.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtcbkcaurx.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtrsjycwta.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtmrmpixhu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvfeurgb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtergzawsq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtwpmuldvf.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gtwrvmgwkv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtndwexadj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gtypobkovv.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gthdgpffii.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtpazqnipk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gtcsqehwxo.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtuqvuzliy.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gtcmxujrcb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtnaegxhrn.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtggvdwjxs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtzjisdcon.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtwlrudtmi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtzehqzwov.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtaavtykck.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgurajinv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gttxiizjnl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gthvsmrefk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtlbzqzxhn.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtahwtvjgs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtxipespbf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtkwhpngin.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtfqprouho.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtyihkglij.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtgvvscqag.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtlarouhwf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtyprldqox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gthvdtaazj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpwlgcseu.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtopafrhci.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttecanffb.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtdcpwkfsr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtiadmzhng.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtsrswpmrn.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtugvhslwb.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtrasfquce.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtfyjfause.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjgitsgmc.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtvwchghhd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtgjqmkwwm.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtbuwrsnzp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtbdsmkioh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gteibcwxhi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtnmaulmsn.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtkkehdfjx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtpghgsvya.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtpvkqugft.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtnlititxs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtcymezeyf.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtwnjtdrmp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtjisdlbwy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtaaqlnfuu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gttlxogtxe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gtrdovganu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gtjxqnynac.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gtdyjxxtvm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gttvuktgax.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhrbygvv.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtibwnpqka.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtmguuhuah.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtafhovoxf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtebbkvqdy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtnxgagdxr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtcjnowdas.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtbbxxulaw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gteyjhtoaf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtxbdwnrts.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtdciwbips.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gtmnywrssj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gtkdxidjio.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtqfvuskak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtxrxsikml.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtgjkyevql.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtlflssatl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gttqegsbdr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gtmwfjuodh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtjtpzjzce.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtcolbhoim.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtjoecsshi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtjazombuk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtpikhfkqi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtokudnvij.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gtrtdiowtm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtsoahbskm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtiaommqou.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtlsipowzj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtmgldddpe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtlehgeepa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtyttosrgy.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtfwvnzauz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gtuxvwejdr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzegrhsm.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gtbersjhss.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gtvouqtdny.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtyklbivtk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtezmefmrb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gthbmhzfas.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtvudhigip.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtaabnxspn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gthmrrhufl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gttprvlmvl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtdxlffhrs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gturortfho.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpwhdhnh.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtimpnbyex.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjzaeyhsk.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gttwjgcbbe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtnredzfvh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtvnatzttw.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtwxcpfjge.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtmpvwgzdm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gtwvnouanv.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtvobwwopx.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gthysmicpn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtdvktdmms.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtkgeuxbrn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtdacjoxnn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtkythtqqb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtcezazpqz.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtztppikln.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gthulawtrg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtuayynjzc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gttgsxqiuw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtxcjjsvrb.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtzaqdjoqe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtqtwmsywf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gtlaghsldu.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtprmlonkq.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtknervbsl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtxomeaxjr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtecrnixjj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtpzaebyse.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtpabipqcg.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtwewwvzuy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtpvidejuc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmcojunr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtqpedmbmw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtgtqxsrfb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtwqfatjma.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtgdyiibek.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtlivsrned.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtlmzpnwxl.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtllzsocfr.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfubeoqto.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gttkqusxad.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtypcwyqnx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gteenqgpdd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtqvdorqgh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtgnxzlcyg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtwewiukue.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtrarbjmnn.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtrypnokfg.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtzuytfyug.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gtiutjvrez.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxkjnwny.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtecybjchs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtafuimqbw.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtwgapsvyz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtaxqpmqou.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtetxbkgke.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtyzswtgtt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtsqjpehjc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtrlmtkzjr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtnrljiady.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxuydkvn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gthrstxiqm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpawanhni.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtharmkabt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtyrzpgvnr.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtwyzffmsu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtgtzmsoot.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtujeorccs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtzrkcxkhn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gtgowcrqbm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gtqpnxciia.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktusexck.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gtvwkukqcn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtrficpgze.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtqqeylrzn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtaiozvhlx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtmjantsrd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtwybuzure.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtbqambcqw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkgzrqei.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtdiqgwcjm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtitchtrhl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gttiqgegmb.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtkbunilfe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtmxlabjsp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gtlclxtkog.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtffiueozb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtylqzrzie.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtxwmwdtoi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtdsvflkpu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gttbytunzs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gtnrbkwfly.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttqxzbxpm.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gtdmbghugb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthvaiwwyr.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtlvhusxvw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtqduvccdb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gteatkcxrm.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtqohhwjhj.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtzbfkmxqh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtubjpstll.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtuxqiulcs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtefzlbpri.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gtrttzuxtr.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gteqtnktht.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtfurlxktt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtbqohqtzn.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gturefjxbo.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtncxdhiwq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtvkjsblqm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtykmclhap.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtnkcaeijy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtrehsobhg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtluwvadyb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtmslwaxxq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwosvacly.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtumifjlkn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtyisdbnbe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtbszhzcbq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtugezbfkr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtckyyctji.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtqpxkugpv.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtgwwgzzgz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtzkttktkz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gthmuxicly.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtqxjaaaar.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtsocqmbcv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtnosblrdl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtngwybqtc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtiijafagv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvemctmq.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtegvwwvrg.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtptzegvdl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gtrcmsmqan.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtcqgrmyrq.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtwvvvjter.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gtsukwurtd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtnpifewlb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gteszjmamq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gtqtdwtwnn.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtdnenubgs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gthreximbv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtyqtfbxoe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtqlyxkzkb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtqsdihyzl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtaxxymebs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtcbdewbot.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtyewkviwm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtonjrktdu.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtlryeivhn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtyqctsbzk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtgwjstlkb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtsfgodxre.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtbaquwtgx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtelmrxzku.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gtrxznwdqv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtciddayos.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtlvstnx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gthjwfdpdy.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtedjezbvw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtqoejezkp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtoorygttt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtyzunqdyv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuntkehmq.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtnrkuydee.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgfzmsdy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtshxswbny.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsflfhyia.html


<!-- 参考信息 -->