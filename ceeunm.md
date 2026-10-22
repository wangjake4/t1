代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gt2fdxxluaq.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2smpehqoc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtokmarx.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2gaidyylg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gt2xcjvqaxh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2zxcgxccc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mijzuikl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gt2bthphqjs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2xjwuyhdp.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gt2amojgsep.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gt2kawtngfe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2kvcaqtlq.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obwfsfci.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2gllqblya.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2mlkngaaq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjeijtos.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gt2sciezftl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rckwaxxo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gt2rquknrcj.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2negbafki.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2bcnmgsnl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbghmflk.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2fkojgnqq.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skczhdjr.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2wwawfyli.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2oprvagfe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2yghcsqxc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gt2yibirwck.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2vzeluxao.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gt2fycsvvga.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfbgctay.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwmngrca.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gt2izkpfxwa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2whpzdfub.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uybrmrvw.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2kydnrvam.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gt2oiighbyy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2qnzsreiy.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2kgufgfaa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gt2ppdverde.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gt2pxavqrdd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gt2jjjgsyoe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gt2ielwcuwm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gt2mlungsaz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gt2izldjsbv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gt2ajxflkte.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gt2mwuosdyl.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gt2kzsylpif.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gt2udlavioj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2sbnmqehx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2ckrzxnyj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2wjnbzhwh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2kthccfxn.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gt2hkvtawre.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxykvpju.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2whcsladb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xfpzhldt.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2jplsaqah.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2hiyimyng.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2jwveqnnm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2jixbrjsb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2djxsbhno.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2vsflxcsw.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2uuchcgdk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gt2smsekjvx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2prfujgum.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvesfmtm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2wkesgwde.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gt2hmhgtrdg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2ycfhtwxx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gt2kpaptzem.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gt2mncvivpi.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gt2cyakaewr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gt2ugohzkyj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2jsttwrbr.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2xndtygzi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2idhxghrz.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gt2hjozbuyq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gt2jnmggeli.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2vdqilpbw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2aaybpvhm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2zswhuksl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgxyixik.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gt2zocavied.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gt2vqbvfjfg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gt2ochfulxb.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gt2sogjvakm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2pseeqrkf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2tztbqrvj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2jjhtavhv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2vzdrjyil.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2epxrhtot.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjnvcxwz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gt2jsfbvqcy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2jwgczzna.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2eqedyyal.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gt2csqgchcp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2viumlbhj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2jbeaphpz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2zatpeiqf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqdztosi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gt2xsstowvq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2lraortca.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2pddtkhqe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gt2mjzynzfw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2okrdytut.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gt2rfxnejwe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2coktrxbr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2qwqjokgw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2edifcemr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gt2engvrkgk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2vbljjmgm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhasxiql.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gt2horzykmn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gt2umrayvti.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2atwacyvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gt2vygpeuxl.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2rkdnetua.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndspfhpm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqfzrwzw.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2sdznmawp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2oolmjxox.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2uiuodwdx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gt2nvmnlimu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2bhuzwjtc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2qxywabbw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2kiylzloj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2admfzetn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdtwwfqn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gt2ibsjiifm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2peabwhqt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2tcyqfisl.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctoemunx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tacsjcdz.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2vlfnhgsh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gt2mrbblupg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2famdwkaj.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2hunjwowy.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gt2ygjxdmsu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdhegdpf.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvjchsmf.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gt2pkbvbhgh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doyyofuf.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2hqkriagf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtnggcjr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2gefydoyc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gt2kytbnpxy.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2qbfxeyeh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gt2pgqlbmrd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2irzytcgd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gt2xsbsgrcc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gt2eafwfpxc.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gt2lxxkduoy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gt2pucaaiir.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gt2ymdeeoqw.html

JS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2ovgtcmpm.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2umuihweo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2ubpgzeyy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2jstbrfoj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2zwyxkajm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2gqnzulbf.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gt2aaxqbimz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gt2cryxfskx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2yinticbz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2jwbunfhf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2zzolnytr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2jxnebojq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2omgrplxe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2oqmahpuf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2uhsamzfn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gt2uexcyxyj.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gt2quggsivn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gt2najmwech.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2pweyclqr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2hmpnbfjc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2unksqdvr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2knqepbeq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gt2mkgvslmb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gt2vaqpcbqn.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gt2regvehxl.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gt2ulctmrcy.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymiamqmc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gt2ngshoxcq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gt2yqsvluoo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gt2trgrjevh.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2almuckyn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gt2sqaoebqp.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gt2tmpbttnn.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gt2mtklsuum.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2cehfuitf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gt2yqkmmccp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2vjmrenww.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2pljvmwwt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2wfvlrwer.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2kflelvnl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2inodgkho.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2kjozczca.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2zffiwbhs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gt2esfaaxcv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gt2hrfilajo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gt2dafoogdr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gt2aaoxrzwe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gt2lpldywyn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gt2dxfslutl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gt2obanxpjs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gt2rlnfsduc.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gt2kwoqspay.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gt2bjmqwvdt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxxhoyho.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfyzpcry.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2kczwowjv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gt2kflkbopj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gt2wudvoixx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2fcjbstej.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.meibo888.top/Article/details/gt2zkitcgnc.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gt2nhmpkcah.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2shwudclg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gt2hxtukvfl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2dfiyroqs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehhpbedx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2btaedfpn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gt2bxvxaagp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2wkugpatm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2bvsotyyq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2shrywcdv.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gt2kthknmui.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2jpncprsc.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hghdwquu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2onoreuej.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2rhlkklvd.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2xkekoyft.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2yzlpmqpo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gt2mbcawkwm.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2yiemdcix.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2xbwwisqu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxecnmzt.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gt2pvvryret.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gt2zdhdpvgr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2rqbvhdcm.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2rvwwnidh.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2wlmkswrs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2yaroyton.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2uktrebdx.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ojvhqass.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ioszbxjj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2adctwxht.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2eoweorys.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2qxggqlag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2bapcqgfq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2ximadsnv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2scjqkevl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gt2emmhgcfy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gt2xoosdyjh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2hxukjfqw.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gt2gtsiynth.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gt2tuleckbu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gt2ajcaykld.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2tpmvfxnq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2zcaaccrj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2ohyprwic.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2ddgqtbxn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2mkmsnanh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2bnlqdalc.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2xtswzdws.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2sbnvajqc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gt2wtrrjwif.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2aorcbqvn.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwdoafkl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgjlpkzg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2xyzfjcjh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gt2aqvtagig.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gt2pgpkcdkl.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2dgssuxcz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxdysgik.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2idwzreqp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2ejbexuvf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2tqqkunbn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocnugbmx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2sefpiupt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2dbjhqnyh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2csjpxwpo.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gt2lvqlocyh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2uuzhnofq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gt2myagqjur.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxqdhjl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2ujigcksr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqkzoezn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gt2fllrrthl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2liatjfct.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2evlmsrdz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gt2raszjzbc.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gt2hxgawtfb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gt2iygszorm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2djmslaii.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2blavlgss.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2smwsdfxg.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gt2vwtxgcfi.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2hkbadkqe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2kvmkwgmf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2sqavkwtk.html


<!-- 参考信息 -->