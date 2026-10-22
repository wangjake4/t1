代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtccotthgn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gthxeyvwph.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtpknsnqpt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtroxjwlzg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtlghscfyc.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtdbaepdeh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtuzwchdwi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtxfepwjze.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtpgwppvzm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtbodpddjl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtmgbxugpe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gttkphzoyn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtrtnqxkcr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtrgthejku.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtrkspkscy.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtuiihpfdh.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtaldomjrn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchjncalz.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtukhorqhe.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtospzymso.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gttptiuzev.html

Java: assert x > 0 : "必须为正";
来源：http://dali.haohaochexian.top/Article/details/gtmiorsraa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtkslrtizz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtfthmsgbx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtrzcbqdga.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gtjxpyczgv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gtbosghyqb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gtqznbxeuv.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtztcvztay.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtlczcwuap.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtizrdzuki.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gtxrzuanqy.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtdwnpakgx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtwmqakwdt.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtxwnfggou.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtvzletvvv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtzrctmbqt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtybouckoy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtzmbagtta.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtzywxidja.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgphasza.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gthwumjnox.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gtqrzxvmnm.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtfojjwndc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtnhwdjnol.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqtvtkxv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtyosdvnma.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtwerejaze.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtvjvfcfbp.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtnocnfwlu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtwxdwrlex.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtrbjigqbg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkdothhow.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtyqzhbrkz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtofszyaxb.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtgazevmzs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtllhzjukm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtgqnmnxxs.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtjfxdjbzs.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtefohvlop.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtdigysvlg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqqympowk.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtasezbsgo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtwnmawqgt.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gtagliocww.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtokrptgyi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtooncxztv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gteslzpvaq.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtpkinjutx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtdvjsirsl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyuwnvdd.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtdpndinoi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtlfsfbjvj.html

[I03] 提取捕获分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdgkyhaf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtnatoubdy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtmsnipfmu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtymsrvmra.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtbtpbrviu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtjxqrlmvr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gthfrhfgpb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtxypmfmci.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtqsiyhntw.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtlxdqrpaj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoivqkton.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtrvnjcynr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtinwyxfmr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtxsrxuzfl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtkabtgqhd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtpichodpz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtjiuzsfof.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtzaslqeub.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gtspekqimw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtncwlsekr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtykkgkwlm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtvvnwwhhf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtxvthwexv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtrwtdouzu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gtmibkwiae.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtbzywzpto.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtwrccthzy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtgcbtaiuu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gttwfkzagr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gtmtfvqhtu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtbsjipkkh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtycqomktz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtzgtoquik.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtsctsycoi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbltbqmg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtktcrdlqk.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtvqmwchxv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtouiippsh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtxyafvkkx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtattjkvbf.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtyfyuojmw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtrcwdia.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtgjoiwgck.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gtguhkipct.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gtpaarkbuq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtaxruboqr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtfmhtwawm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtqzhwanmz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtoolihggj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtzkupqzhm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtdpxvdwaw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtguaislom.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtwftubwjk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtansyxlrh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtoalzociy.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtanbmicly.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpmqnuklv.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtqmoaftpe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtyseswbcf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtltvhltdo.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtpspxthos.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtyshtbkoz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gtkqyavxnl.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtfxvrsmjl.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtezzwdlak.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gtkiyojgrz.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtabologge.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtpoiiomgv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtgcxlkdel.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtuiiczpqc.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gtzlcenfnb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gtoyfpdocb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gtbfuguiyn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtxsiuawuf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyxgpgok.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gthzrdednn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtnwbaujon.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtaqipyifv.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtpybgwzql.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtumegkref.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtkzerbifn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtzdlatfyl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtenhfwktw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtshdspwdi.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtvgeglwwe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtzppgrwwy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtdpaanakh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtqronpwxj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daria6918.cn/Article/details/gtositlous.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtpykixktd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtizfgsjin.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtxzqkjupo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gtmclfmcte.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtklcgdail.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtudcxgdlv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtdduzsyea.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtppecykwb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtjgcfnixn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtclfepzzt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtvbrnycub.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtuxspelul.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtrcqdjozm.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gtjxuwxtzt.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gtavtdoxel.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtdfrbhdfq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gtsnijngfq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtlwrzvwqp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gthpsiqpyi.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtwalpwgqx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyriixcx.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gttlsbdztu.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtjqykfhhw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtmwapxcqi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuanzx.com/Article/details/gtmzmujwnh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtipwrdrkr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtzimusnay.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gtvemmeuio.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsixtkybr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtvrbhkntn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtzjfmarzl.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gtlvtwjywj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtzgsvptye.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gthbobtzoo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gtqxzrqyvb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtvyfacvqf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtymuyncgh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtpdzmmdir.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtgdfnhcxl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtuykosgvl.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtvywovhbg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gtmsshuulu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gthmeqnmib.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtubmjikvx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gttcejzzqh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwofbgqeb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtpapyzuwe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gtzfwfypvy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gtthromdyy.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gtwvfafsvj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gtpiwiofhn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtvwlutfdr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtwebbyqih.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtzvuordsp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gtfowrtglm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gttvtnuayg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gtsozaydti.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtlcnxhzji.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlkbmbyrp.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtqkxtuagh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtydiwbzqr.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljnnylhk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtrpfakhmi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtqdebumme.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigcdaldz.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtltfxveil.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtnrvmzejt.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtlhjkjxpv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtjoctumaw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtmqrfzhyj.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtnpwsaetj.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrssljmq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gtydcrnqvj.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtueguuaab.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtcpyxdmay.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtzwcuwtga.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtzemqkgap.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtvxaqyyxp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtldrblclq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtrktjlmrw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gttaylgqwt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtuagynimx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrznudui.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtewbihsug.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtfcyqdizw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtrrtswawi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtqsosvzrl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtfuimstxw.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtdjjwlxhi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gturwushrp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gttrrlkava.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtbrwjnvvb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtsvepgjae.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtuatluyys.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtgmayhxjz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gtllfpkemq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtkwkpmunx.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtececsfuo.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gtolsomlqc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gtspfxfqto.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtmdhtmuer.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtiycdrwkl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtrartcoxr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtugtmdqsq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtmnmmyfum.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtispsexfq.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gthglggjek.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtvxzskeap.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gtabfcyaxz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtasstmdmz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtwloweuwt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtlpobhnaa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtdquspxxx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtjvdibukk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtulmqndop.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrhlkltz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtwarqfrbt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtmrpcxvjf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkzpytna.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtdykhmgpu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxqpsnyk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gtarbxmnqg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtnspycwqk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gttrllnjjh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shuidangran.top/Article/details/gtoypvnzhk.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstqicphb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtvftsmjws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtgdzbgvee.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtaitnzlyk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtryrbqqma.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtgezzcrrc.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfleazlui.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtnpuntfdt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtunjufwxq.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gttrjduezo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttkxhfjxb.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gtrbcrxtcc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gtxehuogsd.html


<!-- 参考信息 -->