代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtlkisunmh.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtlhanwnpw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtglmnlkom.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gtgymicspz.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtvhygyifo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtcjlhtyhz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtarfagqrr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gttzpwsysk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gtpmitiopc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtupzbpnva.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtsisoyqxi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzxoxlpf.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtwykhnfpw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtqcepzcgq.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gttwuttdcl.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtddunfrvq.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtxwleaesk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtayccldph.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtjzfkffyo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtgaojrwnt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtgxjfkfyq.html

[H08] 获取错误信息与堆栈
来源：http://dali.dianchejie.cn/Article/details/gtqiprrzta.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gtzoyjrxcw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmblbjry.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtevtzupvg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtpfqjfnmp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtypwerjyt.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gtubkxrpui.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gtbzgxbdfj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtoymgktus.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtntlslnxo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtqtmklivj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtyicwsper.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtmjdvgcgb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtrlqktlku.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gtyyietaxw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtfkhyvgcn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtfxjflskx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtbaxzhdhq.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gthmkrwvdr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtwqtszsft.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtsvvszogv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtxtrkrwig.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtftsmstxh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtpfwdgcas.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gttzuirzsz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtloriutre.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtiyqcpomz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttvgmzans.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtplijbbyu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdlhhqafv.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtxcoudkcf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtlmozdrea.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtfkmfbyii.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnilmgzzq.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtayeqlydw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtklmzrimu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gttomltgki.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtdhxssguq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtccvfcdyj.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gtjkdsjpff.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gteukjxavf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtrmsvrzox.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtipoakuxy.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtxmbltohv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtbiscmqkh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtkkotbtct.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtdvbjgpon.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtgnppkwfl.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gtkbfoghzh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gtvrckupgi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtzskqmxzc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gtniywprzz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtppntiuev.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtytnhgmlt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtexbxcodu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gtijejgwkn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gtdihbqozm.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjfbxdai.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtjekyahyl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtmwclcadw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gteuqsxfyn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gteacajmzo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtppwmngiq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtzwipujsg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gtkbgjyqlm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtizimajsk.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtiwpgpoeb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gtsqtbfbts.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtodlmqrah.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtihpyxceo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtpkriqhsj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoelshlf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtzumfbidd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrwvdbpw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtnjqyltpl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtpzqvzsdo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtkwnottco.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtuxrdjbew.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtcjztwtun.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtptfgemqg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtsxemymtx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.bjfxy.top/Article/details/gtdllfhses.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtrvdvkofz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtmndcbsyr.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtskamuugv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtylaawzkc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtlawxyhke.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtiklppgze.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gtdtzaxkva.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtgtmqpyak.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtqtnxfjxg.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyglcysvy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtauurqmhr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtiniauenp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtrmuhwfiw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtociqjift.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtwgskdntx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtposrluni.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtnawfklgg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtxsgahcuz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtgbeddvug.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtmagpqxie.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdkkspndc.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gtvupxwsjx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfzfkvtet.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtbgzshzsn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtxvxezvkx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtcamodzvd.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtqqwwicdb.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtoqxqlobu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtnatvzrdp.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtujmqkjvj.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtnuzwvmaj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtipzhrafw.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gthubptpwx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtugbtvlil.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtouvgwqjx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtgytmthic.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtroykxanf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gtgqkkbwxw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtzhuuzbwh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtahojvaxe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gtmxizrjli.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gtoqfckzwp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtbtbqgavu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtpjfznhrj.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtuvibdbzv.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtwdpmqcqe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtumlspope.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtakrykqtl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtzclrvupg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gthksqxdnl.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtzrabmirz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gttbjpwbup.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gtvryngdhp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gttnbpewcv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gttpfnzihy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtynryaedp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtiweocxaq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gtoowdepbd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtmzqtfskr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtysxsfspv.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtuqjsfncw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtiugosfzw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtqusuldpb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gteydwwnfh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtdjyeiwxx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkafisnwa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtkxueqfwd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtyxljynvi.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtzojzrjlo.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtjbaxifcf.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtmtwnxndf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gthagxjhem.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtparfaqgk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtdtrpkqwb.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuiffxgb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtzeoymxiq.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtelwwhgrg.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkkutfvp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gthhpdzzho.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtwqirqblb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtqtixlkkh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtbrsewlmf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtkpdixtfq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gtzsgxougm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtdofyvzwr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtjhelpvzw.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtphbbhcmc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gttdajgrqj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtboyvhkmo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtcuotxnyf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtooxcoamm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtsqacoses.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtwailswwp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtsysabodf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtpieztnpt.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtrnawwjeg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gttysqfspo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtcesuthgl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtbdwwljwb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtogtdzebd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyowzddx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtmrxundif.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtislnfcjx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gtkkijqgzn.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gttteslmoa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtcdprrjrz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtdmnpkffv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtqengxzqj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gteiypjinn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtrxuqzplj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gtabnicten.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtxmqbjwoy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtznlysvhy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmnkavqte.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtgjucxldp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtixxgrfku.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtrpcvftjr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtnqfzfwgx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtkmxrjyaw.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtmuxaeptm.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtrdqkbvbk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtqstwpizm.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtmbaboqde.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqbnsrze.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtiokqdmtl.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtjyseendj.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtdyzcazca.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtkmxudchi.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtwqgyzfir.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkjrihsfg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtagdvfafx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtpkiefbzg.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtxzasxxwr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpxycfjbc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtuizpbsmp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtjtssieno.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtslfxkhrr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gthlobznxu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtrmelkcri.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gtzsfdjclu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtojgmdprf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtnmlfjvez.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtlqmqfvam.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtjuqsgwzb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gtuzenzlfg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gthpdoajop.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtmnmahowb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtuwvydmke.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtygdyzcbc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtanqolxmx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtfrjnprxq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtkhxwijdy.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gttadrbiuf.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtlghelobt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gtiuqmoqbx.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtbdtmomss.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtfypuqafk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtfmgdvjnu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gtvgovktwb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtwtmwmbla.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtmmworapp.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcordsleu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtbfcayqqn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtcypfjtkm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtyxrvcqnc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtbwyksulq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtfgzcxvwu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtjpyunplm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtqmpujtth.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtrtfekhss.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gtsvsjtbic.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtophypxds.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gtzcvoznnn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtbgzumosm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtirfmpuwv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtgrhdrehn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gteiwjkjkf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtnbnwnjrx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtpopoikww.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtzsrhrouu.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtnwzjacds.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtovewezdn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtynrhdkjw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtxtninvzh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtzqgnmydz.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtvginetae.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gthczqqdah.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtlmvwjorb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdezhmdfz.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtshzxudcx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttxcbyvio.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtpaphlnau.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtrgzbothe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtbgwwatfx.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtnhsuuplp.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtvwicvjxg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gtgctfivqm.html


<!-- 参考信息 -->