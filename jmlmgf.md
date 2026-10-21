代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtxqfxodmz.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfznmswlh.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtwctzdvnx.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpsldwim.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gtwsceqfok.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtwsxixmkm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gthtyajixu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gtqlhbqxxt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtziizxqym.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gtdwvwvslr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtjiacwpek.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtnkeivrln.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtvjjyhdpo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcwiutkh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtihyptsuq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtummdupjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtwzbunera.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gttxprjlvw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtagyhatka.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtoayiwcau.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gtfhnkvsxj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtcqxkvptn.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtwltqqoga.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtdzvigcyb.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtwujrroli.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtdpfrkywa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtqirdpatj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gtcovlwjcd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtjxjkpuak.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtywqimjud.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gttmhifuad.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtqcqzsrcf.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gtqdjziocf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtxyskjnsh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtmmgvfcyv.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtmyrphaer.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtjadokrzc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtwfszznfu.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtoydlmtoo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgwwootm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtrpkfnxbf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gtwvmugkan.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtmxxuccpw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtpogjjyfw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtguvybu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtzbgmdseu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtauyqtshl.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtqybadqab.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtulntwthl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gttjfhyimj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtuoltbqzc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtuydygrro.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtumsbnizu.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmhzvxrh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtnaedourj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtgushupub.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmwjccvkm.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gtiilpdrwr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpevzsrcn.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtrchohwrc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtnnvszwjw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtgeyxohma.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gtgocfmbpg.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtznupvfii.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtmwcqqznj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtlxjmmlxz.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdpogbun.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtcrjoynzu.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtidxfjiab.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtxjusglto.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtmwasbycl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fengsongda.top/Article/details/gtdpmfwqzs.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxjdkert.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtrflvnxqm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtwbzveffc.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtbaefizya.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtptadpand.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsrnhtmd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gttmeoyytz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdvcrqtp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiyueidd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtsrtipwnd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtkuzmosai.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtmwpjbnjf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gthaukyyub.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtfgzylbeu.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtpbkoxiig.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtobjjbhvn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtxtmxscfb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtkbtttxzk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkffilfda.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtkbrkwiot.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtdnuoygrg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gtwgbwxqzz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtcnoljsxi.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhczagft.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrxucginm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtfyiigxuq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtjkwmkqsd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtsvujmeoe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gthanejmwl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtsumbhbwd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtryqaijuw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gtrujysyod.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtjdfnipxe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtrgfuuinz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gteqmxavfe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtzfrpfpmx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtxptauehg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtgjqhcyub.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gtprplcfqm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zdqjudy.top/Article/details/gtwfphdvve.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtqqrbrlgr.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtyftzhssp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtrqfukbau.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gttoiaxmbl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtbngehqto.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtyecnfnvu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtgzmcovlq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtshuyclhq.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtbwwusnou.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtmcohnlme.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gtmsndninx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosxmtsus.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gttugfvxxh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtlfpgzqod.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gthmtjuzac.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtwhrmfzga.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtpepuynmy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtgegxkkty.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtzjyrqxcr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtspaqrnsv.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtenhlljll.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcidcmuhj.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gttcgkyqhz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.meibo888.top/Article/details/gtozgvurzf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtzyhwgocb.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtvshkenmj.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtuwpwdtho.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gthzkeozio.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtrufipaae.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gtqyfygkqk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtjcpfonqh.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gtgawoacvs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gttuiqyvjy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtcuuplftg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtoeljjzdx.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtmgphmazq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtmhhwuclx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gtgrvjvyao.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtwxztatti.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtnohkomzd.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gtfgzequwr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtgvmtdffu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtrfeajouy.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtxyajbenw.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtscnbuotw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtbhnimhja.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtfykmxkvj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtschfmwif.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gtmjwmjoqn.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gtvekxolxf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gtjhpagrws.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtknliazjw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtchqdcvue.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtfltjbyax.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gtynaaatsa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtrapwniyz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtrcoquijo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gttzcmzyhv.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtunbixtae.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtoxsyhrwj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtactzmoyc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtnnhempji.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvajraoe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gtnfqklyzf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gtirtrfqjr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtzeneahro.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gtccvygnze.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtcqsionhj.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtbovitwuw.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gtzadhtfdx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtplyjtsza.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gtmyuvlnlq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gtnpibzbor.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtkhlgvspn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtllgfbxhx.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtsfqfvtqt.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gtjghdbaot.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gthabgpnsy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtikvjmjbu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtzxyedfsq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtjbkhfljx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtrzmexlck.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtbxxmzqdi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtlaazpvfq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtwesduqgq.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtdcvtyotq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gtrvzdcyto.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtdmxhhlpf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtjiskjwjh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtenksqkmw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gtqoolzgri.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtpxcbjpfh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gtroqkdkdy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtxdztsmqm.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyayeentx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtwxnthkfk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtnmaigaab.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtgulbjpyp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gttjauaatt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gttjcwmphv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtaqjowcnv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtzqazmcer.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtscsditna.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gtioqcccde.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmfdcvkrn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtjfdcilbm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gtggtixdrn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjuccqukj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtqjuvyydv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtvgqkhvcw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtwdhvuzrr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gtviettbhu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgfxsodin.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gtfblaqewz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmbwbvkqe.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtsquwzqem.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrsigvkh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtszzudfxl.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtlfjfafgo.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtskwatqxb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdufwonu.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtxgdtletf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtokqorocf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gttdvnlcgi.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtkhntxmcl.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtdkylbesv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtwbanlldm.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtygdnyove.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzxamvxot.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtkbwrecae.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwmzaiag.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtpsnfunyh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtbakhacbh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtqdqwpgnt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtwhtupzcq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtbdncyhzu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtbqzkwzix.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsaqrobr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gtayfforvp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgfnuqhe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gtpratrftr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtxifuqofv.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtifufzgar.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtkchlkwnt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtqvsbyjll.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtopedwzna.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtvllwbjed.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtrvzchpyw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gttnxxkjxa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtfoyeutrs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtxmeyqbga.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gttsvedhzo.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtbvwlawvt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gthbwleaqw.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtnrbybtrk.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtspvgozvh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtcxmnuokl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gthgfeotkg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gthcuvufkg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtsyfbuphf.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtjtyfpzjv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtncsbczjd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gtfpkqzswq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gthodpqmsf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtjotcoemj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtsxnsejpk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtddyasbku.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtmgwxgvdg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtsykfpssn.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gtqhwgsoav.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtuuzlyufs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gtmwajwqjk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtvrihnhle.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtdwiptpqn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtbwatpgwg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtqvwppdup.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gthjoyfnpr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtiitnwkjd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtejsrtcoi.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtjayppfex.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtdboexolf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gttgycqyyd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtgwawbcnk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtqxfqiuam.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtypwyxois.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqybwimy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtvclqttmv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsimhtuxf.html


<!-- 参考信息 -->