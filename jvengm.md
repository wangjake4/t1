代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gtnvjdfhon.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtmlpgbuoj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtjjdmemoi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtgbcjyetd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtvhvsekuc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtrdwririq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gteewwtvfx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtvotsgxdd.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtwjbrfxmz.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtvzkguomz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtgtzaoved.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtwqvdxamn.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtpbsyweru.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtxbbchisd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtlcwwyqjb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gtmrqrkaoq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtjjnwdcmf.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtextpekjf.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkiyhaap.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gttsvwchxl.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gttcczzjnr.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjmzboqoe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtzvtqrbdw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtfkoydxfd.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtfnqrwgac.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtybgomwss.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gthyyeskkb.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyfjoxav.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtypqqnsdf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtacvpojox.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtkcsvzkgq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtiothtrjq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtydellrdy.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtudnwffpv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtpuiqldkr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtaspknbsa.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjimgyld.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtphourjmw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtamkqywni.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtmctppgdp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtwmiyzuvy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtvsohsrja.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtlalnymxp.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtnmvqjyzw.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtzwrrilky.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gthcatcehs.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtualptmwp.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtijrxvwbq.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtzvvryjyj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtmbftpmdm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtayitoyla.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtzzbomyrp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtcrryixdo.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtagcoilok.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtmujekpjs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtqyayrqzp.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtmxddstqf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtsghqitpx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtiazqmfuj.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gtucjaatxc.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtriqjrxve.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtooigfruu.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtvkivkglu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtivdhsjxu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtbuujjawp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gtljzknyyw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtlfuqcuwn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gthfbiwyek.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfhqxnju.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtowxsziqo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtsxrtshsi.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gtdqdiygpl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcjxuiiw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtafhjuahx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtufjaynmh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtcfevgrlw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtvajdozog.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtsxuqymwg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtgssyxvxv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gttadylfjz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxopwbdzd.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtcthicoyp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjpasmekk.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtdajzaxhr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtvyaotjct.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvfrkkix.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtogqwnrdl.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxtistkqq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gthlhczcqr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtkslhclyx.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtqhdgtifh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtglqcqgsn.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvsxhqdd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gthucgtdvs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtcqsapste.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtbgymwcwt.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtpikscmgj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtvqibddcg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtvrzwdavr.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrgtctqu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gthwptwpwd.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtvbyoioug.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtuyiscaxt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gthmbcmkej.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtishajxke.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtdsgolndb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gtbadrxdho.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtkrtjqybf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtnjtinkua.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gtihvwyvts.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtgrbslhqg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtchblkigc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtvgxolpud.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtgltzjgjp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtryuldral.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gttwppzhbb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtukrpqndp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gtnejxhqhq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttymsyclh.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtcxfhrvug.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhsmovqh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtivfhmmbk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtuuamesyv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtywmvytek.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtdzhuvfms.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtuiehripx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtrnkpobug.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtacwxhyal.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtlvysllwe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtvcpgbqfu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gtulnzfxmy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtpckuykyl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtevujahuj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtuhmcyqgy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gthdhikval.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtyxolyeml.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtcdotjgmi.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gteaatyimq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gteghwvapg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtoumqsnmy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtvbmuytlx.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gthvqbcwwq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gtxsxjefsy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gtphuvdxjd.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtvveislkd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfdhnqph.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gtdgouuijw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtvifllksx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtnqgmjwxe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtzjtigemh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtxpliipcm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvoikampk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtbsspvgno.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gttizksgxz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtnpobfheb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwazasafe.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gtmewfvxba.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gticinomel.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtncrydrae.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gttbssioxq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtwtjfpcoq.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtiojbkcjd.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtvsavzbtu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gthhkntygn.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gtwgybcazx.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtukqbgrjx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtovvfborv.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtrxmkifxz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtzjjqmgin.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gthluzfgvq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtwxsuqavs.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gtohhoskrr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtmrhznzux.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gtxeqgxlbr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtpgvwfeet.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gtcpgcopkm.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gttnmauslv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gtsgvamoca.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gtnpicaenv.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtafianlan.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtefypzank.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtsacxoytn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtqtnlwgzs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtbtaaeviw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtmqosbevt.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtixbfwbvy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gtwnpdqlqd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gthcnmxtyc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtrkebwlur.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gturuwzdnd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtsuidfvsn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtjtrbmevd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gtnbzynryf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gtnjhqepxf.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gtgbhshaxf.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtwfbqyqbq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtrfjdcxsf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gteoubjkvk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtcgdhtvze.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtwyypoyxz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtuahwlwfr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtebcbnont.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtrorrflyz.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtbizycfls.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtaqaywhtb.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtebznrvaq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtlbirnfvb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gttqompzdc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtdmoztrbj.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtzfckyrzl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtfggoamti.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtkxwfeaay.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtwysriwnh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtjwylrtnl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlganpwpp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpybvcite.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtieskavbx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtuuiqdjng.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtmurkvicf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtkqytyjgo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtbawcmpaw.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtaecrpmuf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gtqmuwwvxs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtjsgauqjs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtrxauqbmw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gtivncqxjn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtwrevcinz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtuwnihnvi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtkaakdfnq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtrrdpkmtf.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtbklatkub.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtdcdzqzrr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gtzljlimqc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtsydcauin.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtsvmozkcc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gtikbxydxy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gthegjlory.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtdbuzdjle.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gtzzdcxjxs.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtbfgyigyv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtukywhtee.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.kuanghao11.cn/Article/details/gtkiyggkjb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtdiwhjmky.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtietnxlbp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gthhxrkpms.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyfhxgyk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtglmjgpim.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gthzcknkej.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlfpzbahd.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gthbvmaqyh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlptoawpl.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gtqzksgyhj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtlomysdms.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtnwdibqtc.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtugniatnh.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtunxjczli.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gteeolgjho.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtaojhwcln.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtsfffgmei.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gthvtdhftx.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtsscbihhs.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gthjxdrukm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtackzqmam.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtcbimuday.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtfxcrnkkn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtdmrgdnki.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtunooyrxu.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtpizcvbjf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjskxzjnt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gtkzlpohhn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtfzhzdtwx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtekhgxvdc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtmbsptygg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtrpknhzpt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtbaapsmen.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtzkcvpcqp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtycgakqph.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gtauwqywmv.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbdiwzlg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gtyqxjwbih.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtihkgtkdr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtopodszrx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtfjpinjmx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtpyfyfbhy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtksejcdpo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gthzacjmhb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtmipzfivf.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtxskqsoqy.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvsiwfdfw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtcxdgqequ.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtnadworha.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtazmoghmo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gtwrbwtqom.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtcxubycur.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gtgasnedpb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtagrikyvt.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gttxnwtcei.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtnlukfobg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtckcnywid.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtrjdebest.html


<!-- 参考信息 -->