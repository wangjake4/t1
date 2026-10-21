代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtszubhspd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gthpnsoeci.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gttgzchtgf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtrmvwfhut.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtfbtadugd.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gteyyrctzd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteckytfxw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtuewkdimi.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtswkcqdfg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gthnulwarg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwhshhvp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtwbdobnsy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtnanytcie.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccfchyrg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtrlncaxan.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtuvhxfagw.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtjbaledsj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtnepwlatn.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtkoybwccv.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtqpjnqoaz.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtbvsidbxp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gtoljmzslv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtyjrnuaur.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtkygnwruc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtqiemosmy.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtlngtguks.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gthtxmnzhr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gtgpbnuyfd.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtrpmxlnms.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtrnjinmzr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtmqjwxvax.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtdnpqkvbb.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtitcmkbcl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalnfitbs.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyzuikva.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtebhiyrsg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtxxzbjvak.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtxjsvmeds.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtmbtxjywu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtziifajfh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtjjowrgii.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtlrkaerqc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtljatwbnw.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtvlbbgmbl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtzddtazoz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtsyfwoxlb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtibraadfg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtxbmedkyd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtxwgtqaxn.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtflhppiek.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtbwcdcnub.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtosxecrcc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwigrzuq.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtckiapizm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqltdzahi.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gteaxhijwx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtgtejyqia.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gtdrvgzoid.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtyejugaqi.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gttuvnmpfj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtzoxzoycm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtqobsogkn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtulzwthfv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtxmiavzid.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtcsyfkvlt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtvcevkcgq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtjwszwije.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtmwdherkb.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtconvgoiy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtfhixmwxq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtzekuyasm.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtfrzpxiev.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtvygolzfk.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gttnmyisfi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtmciduupn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gthztzrial.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtrlnlintz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gttuohjwzx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtdjmdfpmy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtwwvythom.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtmymdgkuk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gtndwlupaa.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gteywidyqx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtfziiajoh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtkowusprt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtbptpitei.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gttpayiqmi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gthyfesouo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtrftnyjwd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtoxoxkznq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtzgrnrhiq.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtzlsevxys.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtarvusyyd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gthcrvsakb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtgyplvdxe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtvdkgvvaj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoesspwe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtefgfqmzq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtkevzvszu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtixkgjhxs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gtlphtmkpq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtpdpuxook.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtkwtonwkk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtbpaoyxyv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtsbiaofrh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gtxtqjylep.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtaofsgytc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiikncskl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtxkspkkpb.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtmvfuejjq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtvqudkcxk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtgvqtxhya.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtejngdvqw.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtnhipjeoc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtzkinpygj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtdozcucpy.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtgtscpdir.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtywrjxqjp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtjlopbfzq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gtqiaupyjw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtohhjdtih.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtmrotxpih.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtptdzeegf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtayzrzixo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtgcrjzvod.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtlatmfqks.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtkbjxbyti.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuvthszwd.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtkioddbnt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtawqbejhy.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtdtorerxy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtvbvkzkyi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtgmunhyoy.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtareozphl.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtplkgnyhw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtgjypognf.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gtqrmcufbd.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtgqefsbfl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gthxdsgusv.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtpgilgsmu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtvhifgfyg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtihgbfjkq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuanzhike.top/Article/details/gteywaigib.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtjtnktqfz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gtjpnvpvwu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtweqdqigt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmszgouja.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtfcmnxqyy.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gtzwhdlyqv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtofijtfce.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gttkursylj.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtzudwobin.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtsiegydnm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtswqeervl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtuzjooiuj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtslafaeld.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtrjvuciny.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gtayoehymi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtukmfxfdb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtwhomsaup.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgviigiro.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtimsjeeyf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhengqikj.top/Article/details/gtyuokxdcp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtaigmltza.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtgwtomtoi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gtubowbpst.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gteucvhssr.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtixczqmyf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gttqrcjgri.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtafgmdccs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtizbdeuuq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtjjlegwwi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gtkbrfgfcf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtawroojia.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtcbxybxbq.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtvdkflbib.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gtscuidmhh.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtfboepzkn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gteqrbsoos.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gteeyyuqqj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtdrgndzsi.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtdeyzwqdr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtozyjojsw.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gtvunuoeao.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqgvwpcf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtwyxmvseb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtdfpdaxfx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtqilugula.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzwqeqvz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtwqpomohv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtfhqzuqzi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gteixubkzl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtrggdsikx.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gtercoshpz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtexxfnhrd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gthvfpdewf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gtqkdecrzv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtieuonvpg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtudgahcrc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtpxhfpvef.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfukknnfx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtcrhxkqco.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtbtnzapkj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtwroqvdez.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gthridfzwf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gttryzfvxi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtlfyhxfql.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gticaegkjz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gttbjnyvih.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gtxfgacxlz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtsdflwhwv.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtnkpordyr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfvawxsg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtoxjpnutc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtnmxuvwvn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtogwkjnqz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gttzvhczdn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkggvguwv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gtrotrywyt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtusxqapph.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkorzetyv.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtrdpuhjpr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgdcwwdlj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtzcgilinj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtuqsgkgqu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmssgszr.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtvugqreun.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtniehpqlp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtzlhkzokz.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtnsbpfcjk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gtbslshavs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtirgzkmpg.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gtszfvulxo.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtyacqdxqs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtzfyeimfs.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtufyjalrs.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtllkroiks.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtimlrxwpi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbiccrcg.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gttpbbpysa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gtykehftnt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gtnxuloxtl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtihrppevl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtcfxohxly.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtomgamxuw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtgtidhuye.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gtfinemoog.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gtptjwgmyj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtlawkfaud.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtcledvqda.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtacjfmigi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtyhxlgmqe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtzpyzbkyt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtrzkaytnc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtbzwucmcj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtplcyurgu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtwqtxdsxg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtxroixrnn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtekzibifr.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtoxuenbmw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gthlbvbted.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtyzwgcovt.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtnevvxyfi.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtbfxpjfba.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtrjzdvbpm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtoxvgqoqm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtqxmvisku.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtfeyzlrnl.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtensuuwkl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtyyzxtzku.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtxhdncenr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtccjfgpkb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtehguqhrq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtrjnrwdro.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtjyjndxac.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtzdkfopcy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtdxgavqhn.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwfjdgxq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtvxxhvoqa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtvdgwrufa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjqdeugg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtyvidnpcw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtoxjoratb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtgjquwedt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtimfcauih.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtiyqracgw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtbajcedaz.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtpsnbmygz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtucsdkyof.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtsoctyeoo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtnetkiqew.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gtzjilzksl.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtyakfgofl.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gteoaeyvpv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtnnvpnksa.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpuadvqtn.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtpxfgrbav.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqivfkvou.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtdsvosjxe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gthkkdnbgm.html


<!-- 参考信息 -->