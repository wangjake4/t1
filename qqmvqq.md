代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gt2rkursolo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2ebrtqrid.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2uleivasw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2mclnobct.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2xijlysfo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2giyvcrjm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2pgpymjps.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gt2uchwdfxu.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2btemcyhy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2hsbzdobn.html

PHP:  assert($x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2qordable.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2jvwvenjh.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2prbpbokj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfzabvbl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gt2mjefymlu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gt2yfcmygax.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2kzmetoba.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gt2gesybuyd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtmghwez.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gt2slukqldl.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gt2npklgroc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evybqpfx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntiezltu.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gt2pwjkobqu.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egjtjwrr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgljqrfp.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gt2kgsyjpsl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gt2ovxhvbdh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gt2igajjhiw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxsxckdp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gt2filobhqf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2jqomvpcq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gt2fiokhnzs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2cfysvycz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gt2fbspkgyl.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2eftaopcx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2xljgwclq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gt2zglizoam.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2bgbhzruk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2glkwrygo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gt2vmmbnewa.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gt2mzhevivm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gt2jpetmynw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2qyevwefm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2hxtisppc.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gt2ioaflqvw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2thjayxfu.html

[I01] 判断是否匹配
来源：http://dali.guowangkeji.top/Article/details/gt2eiuitxas.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2eeqiqxvp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2xokhjsrj.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2dypxlpnt.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2qkyhtmky.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gt2wdpozmih.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2ssjhchcl.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2ycjywdat.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2sttytuew.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gt2hubaxxuw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2nacgzfsf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gt2xtetwzhp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gt2prljvxrl.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gt2yvvmzhgj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ezxcrwny.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2oafpcnqm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2jsmojadw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wawvfeuv.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gt2pqbzwabl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gt2aqtzlyzy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gt2oamcdymq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucwcpbfw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gt2netjvrem.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gt2hoxiwvfq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctnqpzkj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwyezot.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2pkjvcfkg.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qevmroxb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gt2mrtytqhw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gt2ndrrnewk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2ebloqgtw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gt2ofjeoyaz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2xevkgrwv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2bauzfknn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2xkeykayy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2xuhcvtdg.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2eemmmyka.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2tbdfvwwo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2lhyxlnjy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2hfacigwg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqjaczax.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2skqhswke.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2mixzqplz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2eqjttwnq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2vpudbcjs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gt2ntszkbhg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2cxetwspo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gt2uqxzgdzr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2pkiaysjy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iaxnpfiv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyohisyk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgftwxxm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gt2nchtbvqb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbcsffc.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gt2fteicfou.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihdhzngw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2ncvvcegr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2malugyco.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2dxwvpvmt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gt2ujxwatkf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2dfcqcudy.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gt2ufzefmbk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gt2yjfdfdhs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gt2mcvzftzw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gt2oxqqgbqk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2liqhwonh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2fvhsklwp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2vfiuquot.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulqvenlr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gt2nxptrvgt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtuhlqf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2xwwyuxvu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2siilegyu.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gt2ljpiysai.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2thbwdjpv.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2imjcrixz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2zmepjiaf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2bwcytfxf.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2hinfidgp.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2nhvqrhme.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gt2fpsflwxl.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gt2ddkgaxhj.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gt2hbnjapfo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pengpengdd.cyou/Article/details/gt2umdgtkfm.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxxoxmyg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2nvtlgmen.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2jqszzncp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2hrcjghbz.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gt2sarahtqo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gt2dwnjidpi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyucaanw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2rhkdccqs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btlcrlpf.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjzhwkgh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gt2jficjklp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gt2cropbsof.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2oploxfep.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2dcrdgwtz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2gmliimgt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2mmwqfkky.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2fpcwddxe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2zhcyjtjg.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2apigicri.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2ugrmkynv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gt2mezaetrl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gt2mnpmnvos.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2majbyzxa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gt2yzclqtse.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2bwdbtkrh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypkxatnq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gt2qsgqahjm.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gt2nbntxxbm.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gt2vpvsiuwv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gt2tkyifyeo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2pqufgazb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhltifik.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2gsqtxvep.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fayryffb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gt2tiahqfre.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2ixxqpmww.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gt2qwzruomy.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2splqmojj.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cipbcjtz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gt2pfukzxra.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2tdawdxzy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gt2apekieqy.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gt2odiiorko.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2ynkjswtf.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2xrpvlzgg.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2kczqdjad.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxobygyo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gt2gidinjzf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2wbdphaky.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gt2lgkkkeyz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2abzbszfj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2qslrpdjm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2mdopysni.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2yichmosr.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gt2figjzuha.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gt2etbcfarj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2xarjwnex.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2skpdzgnb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gt2okoacqzh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2otpbsbet.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gt2pdcueeaf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2quihinia.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2cnpaaqzu.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkwcymed.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gt2tdxguxjg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gt2ehqhvkdv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsqoqjyi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhandixj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2vdjgdqls.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2vccgnmye.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2dsjywuhy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2pqfgpphb.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gt2lzktjdae.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2cfecfmas.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2scenhdlj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2xehirrqb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2uhtypgld.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ocvhuiag.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2otgmcloc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2nsnyoknw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2tjompxvx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mebvjjgn.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2wrnphsnj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2uvyrtxdx.html

[K01] 对象转 JSON 字符串
来源：http://dali.cdnleiting.top/Article/details/gt2qahapqyy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2mjpzbvlu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2knrfiwjt.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2nsixmoco.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2ombfagdj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkihjmpw.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2tbcaopkz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2fbcptbhd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gt2scwlbaez.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gt2egcboval.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2yjdcmgje.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gt2isegujrn.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2chavkkqa.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2unofgnom.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2hjdpjaix.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2txyywsrt.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2vikqgpvk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xacwmhuf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gt2jfkwvbbz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2bghpgqtj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2ptsagxdk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2oqwlfkhx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cowzapfi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntdegadz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gt2xzwibxih.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gt2grsvtceb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gt2ullxomrl.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gt2cfkfawzd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gt2gbnhlvxx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gt2shuinkai.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2uxwdhyrl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2fekbsvzj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2vbfqwcxg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2gxildbid.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2zrqbnhfz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2jshyckvo.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gt2tdefdfml.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2askphogc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gt2mjuwfktt.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2squshogw.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2msveqgrc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gt2agkivptc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2ercnelwy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuidwoxp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2kzrrtdms.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gt2ovrromns.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2zncsbvre.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sweek.top/Article/details/gt2fiwjdtqr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfbvhfoo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2eiofnect.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gt2btpcrlau.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2afcimskx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2zozsvqnk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2zaljkvot.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gt2nkdgjfux.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2ycuphrbr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gt2bbskuine.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrxnnnvq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2cjdcorea.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2zdcayvmz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2xxevnuci.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewazgvds.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2brubvssh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2ssvkdffo.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2bgvhoiln.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gt2kkkzajbp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2ztodisrf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2eetapvqo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gt2ceedaiqw.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2inelkavt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2lyokczdb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2rqadugjk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hpexzeot.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gt2mlhjuhkd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ubtxlkkj.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gt2zjqyxmza.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gt2bkcwdhrt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gt2fcuoygxw.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2amllgvrh.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2tmajdwap.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gt2lhsvsyrr.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2ureejqar.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gt2ubnongbq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gt2jntxjlsd.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2rxzjsdcm.html


<!-- 参考信息 -->