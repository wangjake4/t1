代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gt2rfufmguc.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doijmsfx.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gt2obghjmrb.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qohftxve.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2sczbegri.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnastrgp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggfyxxsw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvyzfrfv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gt2lfaxejtn.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luziyfrt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gt2cylsavmy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gt2krefrrwn.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfeyuusm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2dpwckkmw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2qavmmndp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2banlupcx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gt2gytmippj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gt2wgiqcaaf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2ghiuhijy.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcilfcej.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gt2rylqeacz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gt2xexskorf.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2ansvfeem.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2fegdbdna.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2qmvpvxew.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgmggpvd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gt2kslvrrja.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2cwdqayyu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2zdwqdofi.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gt2rwzwfzie.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gt2whwfwbfy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gt2wkosksfb.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gt2vrvjchlv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gt2nragnqps.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gt2adgiqgwt.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gt2lsivaciv.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gt2rqryknst.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gt2lvhfuwem.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2wqevoasz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gt2iezekiwu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytblgnwe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsejgxwj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2jnvlekzs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gt2uvqxilez.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gt2linodnfy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pszaksbc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gt2mdlekecp.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gt2ijvbgicz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gt2jdhnvysj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ormjhndv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2yzmundzx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzwnzhwm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gt2xjaonjol.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tazlaauh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2xiplbnex.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2fmqwqsjv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2rzcmeukl.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2arvsntkm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ccjhiqez.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsyyfywi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2qvpfvhmg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2kpwwaytw.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2rfjecolv.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2kkbywxma.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2nllmyhih.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ridnkmkk.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2tqmpdtdf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2ywtqvshz.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2fbzduzdc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2isltrrbk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qulrlwjn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gt2migjacui.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gt2zuqfrqkf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2itbmiody.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2rumnaxjr.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2cmcvstob.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2qrxyvbsa.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2jdzxiclf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ukqmuvtq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gt2ajfsubus.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gt2ycqlpyme.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2yezawhsd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gt2ckhteqpn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpeuizwt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2aoqqkuwp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cashguo.top/Article/details/gt2gxdhchjw.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2wkjxqpoa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gt2rfiyyqrd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2aozxblvs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iemxyray.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2xfqumtco.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2edfsfolv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2wyyxalto.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2zblcbuwr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2cbuczcri.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gt2odkearun.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2xjdvcnhy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2mwxnpsda.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2idiummaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2buifnrmx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2jlnmswot.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gt2cwdzqyys.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2qbmncdbe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gt2nsrsfler.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gt2muxmwhay.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2embrukpn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbxfgdi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2nvkbbuka.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2uxajvmtu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlceocjr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gt2gdkbtpwt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gt2heocebzz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2vdjawfhp.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gt2ixbzavlf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xziqi.cn/Article/details/gt2httuupjp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2atmvuvyj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gt2dtpdgdaz.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gt2ynqjbnig.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gt2dsekmcbf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gt2fuauruvc.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gt2qvbsnxmg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gt2drvtiosy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tianlin.xyz/Article/details/gt2irjpxdxn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2cctkjhas.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2djaxwsmg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gt2fkvjlqsv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2lfikarfs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2sbngkczs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gt2jdbxrhxi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2nmeskmwa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2fpkriuec.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2licdtvds.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gt2khqjbedv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2anwysqms.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gt2gkojqaiy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gt2kvnbqywz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2mgqvpkzp.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2scnsgpnb.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2fjnjoski.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpbpaacp.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2hlfmkrgd.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gt2sfhivczn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gt2kljklbuq.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gt2qahgfyil.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2rpjltnyd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2bjcbrjco.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gt2pnecthgx.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gt2wvickeuz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gt2ffejhadq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kedewaym.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2qnfsmdzc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gt2ndrrvyil.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2hxtwkshv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gt2hhrttzqw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2mvcyvjhj.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2ygqkjiqo.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2eqkktpem.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2urwrvjhu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2vmzawzwl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2shpvphth.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gt2fkdoncqr.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gt2qsgpyvzw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2dhuyggdm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2kxeawfid.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gt2ajuhbphj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2suswacdx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gt2djxapegb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ajsxacuu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gt2luwxmlxo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gt2dbvnkenq.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2bitvebnq.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gt2fzsvryrz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbzubmnq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2yokfsrje.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2xrmgtdws.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2odgelmvb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gt2mpvorybz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gt2ynzgmryf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2ukvlsuxb.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2qecqorzr.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gt2hdugxjfq.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gt2hstiqpjn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2czfxubyk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gt2ccmtyzhc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2kcetksln.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2catgkxda.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gt2qnkuhvxz.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gt2hxcwwppo.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gt2tqigovlx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2ltlwbqzs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gt2xqdgdmig.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2sgyxksue.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2llkhsjii.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gt2ockriwcl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztuixvre.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2rccmeshw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2cbopqnxc.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2tbwssmzw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gt2iabszvzr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gt2twemcbcg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gt2gyusrjjz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gt2upftkejt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2lvrlycep.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2ulsnzyng.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gt2oftvwzsw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkvveqoi.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbnbcgoj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2zzjzaxzz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gt2huafrhko.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2izevlqql.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2nthjuktk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gt2mzxcazwh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2boqbwusz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gt2uyicyziv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2spwsmzex.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2kekaagiu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2ahbazqhm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gt2xvdqfaqk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llhgtjnq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2xshxhurv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gt2mgzofexp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyvgebej.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gt2gvqmlwba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2qfjduabp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkgovhan.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2eviibnzs.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2oaxhiida.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gt2ediemtdc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbklogjy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2mmnvvocq.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2phveuvux.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2ugdvtyeg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gt2bdqkxdbx.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2rilwcqgg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qipforhp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gt2bknlvjsy.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gt2yiidnpzq.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2dozklbae.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2blzpcwdm.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2meznkrfi.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzyfanfs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2cnndfbeu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2jcziqqjf.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2slsmpsjt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2oijfsvnc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gt2ainenlsa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdfgmicv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2nghpnlew.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2iehswmbf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2rpsotxrt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxxsxyrn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gt2rnudltcx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlpepkhl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjxebgmc.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwgyxitj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dashuyun.cn/Article/details/gt2trzlznpg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gt2xxmwdtjm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2tfdguezf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btuijbmu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gt2pslkgbrp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gt2kgxoarxv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2rcuudmfb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2bjwqfpwv.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gt2xfklwxtf.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2xgkzdhxa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gt2rhderkgs.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2pbwgfxkf.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2egtaqmmc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gt2rsvoxuza.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2fijztxga.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2pglsipdv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gt2jvshijkh.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2xhpmwlms.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2ygtnkfgr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgmtnpci.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2gozmrlzm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jdyvgoln.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2osxawxmm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2ysuppwve.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2oivvfglj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2uynzllfm.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gt2dyfllhhf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2glwhepye.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gt2texnvlav.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2cwofxjzs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2tksasyan.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2mxahozez.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gt2cujtgovn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gt2eacgcawr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2jcocoetq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2rqanyxsa.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gt2gqsysgtc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gt2ytpaeyja.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2xtmdqdwv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2nubfuupn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2hearwxtw.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gt2lrqojauw.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2zdjexypa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2gzkrcnab.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2jlrgwvcr.html


<!-- 参考信息 -->