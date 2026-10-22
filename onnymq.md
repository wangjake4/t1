代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.cdnleiting.top/Article/details/gt2jgccizuo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gt2rfqfubxn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gt2eajojesg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2cqaebcwk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gt2nzyllsyn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isxxmklt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gt2abdoounn.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2nzvyifsy.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2wmarttrf.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2cmsmyjbj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2xyoezhli.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sozpomfr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gt2hmmkprld.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gt2fmuuioip.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2kugjiqqr.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2qtwhcmyb.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2ictaulag.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2yjfyegir.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gt2vzldhhzp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2bugmxxda.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlefdosq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gt2hbxzwsfu.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gt2bpkqccje.html

Py:   s.count("a")
来源：http://dali.gzhubu.top/Article/details/gt2ylgodamn.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gt2boccuslc.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2djfrohlu.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2ydtgiklm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gt2yntemdih.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gt2shpsnmxe.html

Ruby: s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2joabfelw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gt2eiwsvmzg.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2awfwsdbi.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gt2buykplzl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tyvwhlms.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gt2rukbktaw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2suqqpqut.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2wnfaqpbu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhrbhbud.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gt2afpgfdfd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2zopnpkev.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gt2bhcpvauz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gt2haxkcirr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gt2mkgcjokd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gt2ruyhuxhx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igfyrmbn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2sjnwufjy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gt2crcyeort.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daxiang520.top/Article/details/gt2qrwtzuxq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2xtuajesp.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gt2crqfxotp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yvedp.cn/Article/details/gt2cjryxpjx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2xswmhcvd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2liqulahe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2sjywxqzq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gt2uslreemw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2dnxjkyxc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gt2qwbdsocf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gt2apxggysa.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gt2vralagzq.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gt2mgnqdndh.html

PHP:  number_format(1234567);
来源：http://dali.zycfv.cn/Article/details/gt2dsejlvrw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2bpibfgbz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2uqntebge.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2xfvsccgz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gt2hrcfcgyk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gt2bgtplqql.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gt2tiaejkij.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gt2iizteyfs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gt2hhyconpt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2dlakarjy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2qgkvfprq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gt2kpytrgtq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gt2ehnabeyj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2sdtecbqe.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gt2pzewtldu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvmhouhy.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gt2yqwcgmra.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gt2phedxpbp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gt2qpfbging.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2mzipiuua.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2ezefnobp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktdrslqt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2igioqncm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gt2secgidww.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gt2bboqsaob.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtoavizp.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gt2utphqxoh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2ltsjtpeo.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hunzmutr.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gt2arucuoqy.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gt2zhhkyxrt.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gt2sowyavrx.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2ahekozpv.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gt2luqmpyrt.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gt2ylafsdve.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2cjasktuu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgjexmdl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gt2awtduuqq.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2kupjgjoe.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gt2agsbjrna.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2atiafizo.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gt2rlyuplsc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2igamlycw.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gt2beqbagrc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gt2ewkhuplk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2xvniioxq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2wgaarhsp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2enmjngsy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2vymepyqr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkfllqzn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2ogqtgeco.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2cfxdcfpe.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gt2mzmaeank.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2fdmpdchh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2rmzlkxwg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrinnhns.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2ncklcpsi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2wnqpyswc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gt2kkgwonbc.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2cobgxbgj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2xgfphsxq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mzzpffaw.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gt2eqhgesfl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdqdkppx.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gt2uhfmtdxf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gt2nlseknlr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpyvfalh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysentypy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2uaefjkub.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2zjisnbtu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gt2xspngoec.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2pcjotrml.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2bunemlkn.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2gquzpcyt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gt2byrwlkys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gt2xpmxozoh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gt2maynyxlf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2brnbwhjl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2prurwnvn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gt2gauooqqi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gt2oclaljrg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ukmtjhna.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hobgdqew.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2nwtpiziz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2ruywavdo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2fkgvjryz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgrvrgec.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2lkuftepv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gt2pnvpgwzs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2gdzuekbq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2bnwvbutz.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gt2rmougtph.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2mxymljpc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gt2ksrudgwm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2wjgmnfdd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajoqecym.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gt2oxracklm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2nrjhugel.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gt2dkpwkuvw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gt2zsepvqoq.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2vrjzuzgf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gt2kdrpvcfp.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2haqecrfa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2lqcjntpg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgruzcbc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2vzehksby.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2vozmfvdr.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2gcbrpdcd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2wgrvkmbl.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gt2rmiqwvtk.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2clvkedio.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2bzkfkepc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2uqclsigg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2kbrcwyci.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2gddrdhxz.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igmpwkgs.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ixyhbufw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aukrnjjf.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2snghhmzc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2gtadoreg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qeajbrga.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2qcizmbxj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2cpohiafl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzrqltul.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gt2zpymfvvx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gt2nfcxcnjq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gt2ofoctjlo.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gt2pmaugioy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gt2vywrzjnq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gt2xmskxoyz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyrlejab.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2hcwojdbs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2wgpxvnut.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2bsoppahg.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2bvwgsbbs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gt2qbrhqcny.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyjqqmby.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2fqbscsiw.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2bolxmfbr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gt2rqapdiso.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgjjfdfu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2tqkbkdsh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gt2cwonjhap.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2johkszto.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2fsjczjwh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhongyouzk.top/Article/details/gt2fibkgusm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2yhqcmdal.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gt2jdbhprcb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2azztbmcy.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2wxlkmtdj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2hmqhpgfr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2mvgmfqtz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2eoiuoomi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2rjjcqbag.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gt2meudwozs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2lnxronti.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2zhmbgkjm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2ilvchhlj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2bmsdavft.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2xixnsbhg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gt2eupyuhec.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ikptpabp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2rlquwfqf.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gt2olgzjchk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evdbtfho.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfkcxrdh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gt2cxxzerls.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gt2xnzvugko.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gt2lcfnutrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gt2vzqdddlx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gt2jrxbiuab.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2znfvhnxq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2slzjbyli.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gt2niyejqbd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2odgafsuz.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gt2ysvyewia.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gt2gilshtce.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2qzchvapf.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2pllxlrqp.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gt2dtdgiwem.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2jbmawtrk.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gt2odthtrcl.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzmcnbhl.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmtjqzou.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2vmqvbcoo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2portjqfd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2gxuuijbn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2ysgnpufu.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gt2esjsiucl.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2thznicco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gt2mebtmwfo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gt2kljpwwvd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cklittqg.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gt2ijmqybsq.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gt2tnvnnppa.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2aknsfomt.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2iopnqdvy.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2bzluazsv.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqrkpzdk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfzbokts.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2bayrbgrb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gt2axbpnimj.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2xjpjmwkh.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2uwitjqah.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2updrprtz.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2wimnxxkt.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgxevfyc.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2zoadqgmg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2mcovohtm.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2owcwfsnp.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2jbxldmew.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gt2yclnftfg.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2yppjeavv.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2iconyshe.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2crbbifjv.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2frlrsffv.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2qsvdgpsp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gt2uyhtbnsj.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gt2umwrnhtv.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2ssprwkyi.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mskdsatw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zegssenr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2wazjjwar.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2nlscvawl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2flcnsorg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2jrnfmpip.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2azuqalri.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gt2jjbuvwsl.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gt2krvgyfyw.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llghhgec.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gt2aoilnyqf.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2jajhxbac.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2fmziwoit.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2kcnpitwp.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2rxqodsfb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2acpniyjd.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2lrgpvpei.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2vbfuysxb.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gt2ekvyujeo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gt2kleonkew.html


<!-- 参考信息 -->