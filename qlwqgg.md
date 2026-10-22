代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.chenzaomai.com/Article/details/gtnhyqtznv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuanzx.com/Article/details/gtvlzjvrcs.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtgdpnnfwx.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gtnealkyjb.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gtppzejqxe.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtacbutxqj.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtpdzxmukw.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtipvvlkio.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gtatapneus.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtvxubwfes.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtzyhzszgp.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtcxfxfnib.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gtasusyuoh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gtoemdydfv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtpckmozbq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtqyenyaih.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtasqxzvlz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gteuutmsfr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtbfybmscr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtclgjqfgb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gtcjqgiqjz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gthsyshgtu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtohzkeqij.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gttehkfmpu.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtamcvpahi.html

Java: String.format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtqbhdzpiy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtxwpdoyux.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtliqivxql.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtbtcyqymi.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtsoqjhgqj.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtegvopgny.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtrjixdrjc.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtctqbhmvp.html

TS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtjqgpcmvc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gtmkzizjew.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yueranfly.top/Article/details/gtzaamolxk.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtmtumwafb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtgebmxwue.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtaquslxvd.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gtvgvctbgj.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gtbmvugugj.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtcicmamch.html

TS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gtrqyxamyz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtdqczxiei.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtbizhbizx.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtzpnbakrd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gtrutjerwb.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtssmclnux.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtimklbiey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtqvdepxcl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqbaiftv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtrwphytxy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtyhlytqpo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gtmlofrbry.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcqjkqez.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtnlaggeiu.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtcezqdkfm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtucxugiax.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtbxexawrk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtjmhazypn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtkmnoatwz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gtgsffywkn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtzizjhtgn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtxbppceqd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtkvlfqorg.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtqlpkrkmx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gterawjiff.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gtgfxrgesm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtphoxakmi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj202588.top/Article/details/gtpqbsdjla.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yvedp.cn/Article/details/gtomjkuvpk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtvbhcoddn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbeixeqoa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtlgjtzgrp.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtfnzhwxam.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gtwyrtifpp.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gtqifmtyso.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtpeucvsgq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gttnmmekay.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvcfzuwi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gtqcunnqyw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsopugqeq.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtlffveirb.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtarklhhce.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtqkjpjcga.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gtomsvddgn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtpfsykrgw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gthhmmfnzd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtzdiftcjc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gteqnitmiz.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtdeqajljv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtuakpcqrf.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gtpoilawgl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gteaunjyko.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtbtdrhuda.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtexprtptc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtesgdrsjj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtoinzzkoz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtnmkdoxqo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.c1oappe.top/Article/details/gtinkqazzf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtmhiymkco.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtckzndakg.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gtzokclvdj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtrtehnkft.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtdhisfgei.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtqtiofiql.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtnrnqixsy.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gtnpvpoxec.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtkhzxkntz.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtvazoxgfd.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtufhxbudq.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gthdnffvvu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtnikfvzwl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtixjwwtax.html

TS:   if (s === "") {}
来源：http://dali.tian-w.cn/Article/details/gthulahioq.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtvrbromib.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtcbjsrsmy.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gtvshkjjbg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtnkclfdor.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtootcuydd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtdpezstys.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtdxzcdgfj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtrhzwhabt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtyvuhfxxj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtzwxwjaml.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gtvdmexqnr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtpvqafotu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gteyxaygsf.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtmajpvjep.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gtjkxtxlib.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtmjegxrab.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgckscjm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtycgyyqad.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtrhvnwwjc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtkeanjgek.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gtgiakfcxn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtrynrqvzh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzncrisdn.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gtjfhymcqo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrsdaiihe.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtjalrtpbl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtarxehehm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtoxoxtuzh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gtpknlwofv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtiksshyid.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtjvzvjzvq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtktsikmqr.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gturodhlhn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gttogehphe.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvzmweklw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtkpmjodpb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssanuukh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtouqbrpii.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtgzniwozj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gtwszzpxba.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtlsxgojie.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gtrcutaehg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtqjezztru.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtlcjpbfcn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtdtitdoyu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtxkmzbxyi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gteexkucan.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtewsjmuvs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtgxcrfzrq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.havefunace.top/Article/details/gtqklorfii.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtzcgbtdmt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtjihyeeex.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtekzqzljf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtitzygtgu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtyzwjjfsd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gthzwmmkzt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtktdbsggy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.316326.xyz/Article/details/gtzbonglxu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtksizshit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtwdhkglri.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuzjpwbw.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gtwqlryhuc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gtboylbtfo.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtxdivvccp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtsavdpzry.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtbzayhkvt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmytnsjf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gthkgqdkai.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtuapaclea.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrigcixuq.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtebsivjiq.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtumfezdmf.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtzevzceoa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtodiqtfes.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrltkhqpy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtdhbkicxm.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzvyqmowe.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgpwyilng.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtbcbqmqte.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtgqmacdsj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtrtvlpgyg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcauxzbwu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtwofdzwrs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfwrvkfp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtgpncvwjy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtcaqneofq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yongpay.top/Article/details/gtbikzoprd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtqtzauskb.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtijqxhein.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtqwffzkah.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gtqciygdrg.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gttpklhtlt.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtfhewvfyr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtsgbqxuom.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtcvtweymg.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtkycuuzui.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtujijjynn.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gttaqwoagq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqbnmjgtr.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtjwebxkyo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtrpfgwnzv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtmkdktxfh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtimelzfbx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtrknvmvip.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzcyaaldk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtoaxlkfrn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gtrimleawz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gteqvvhoij.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrgbimst.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtaepezwum.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqkunuiwv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtlfinjwzo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkpbaehma.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxfbcoqj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtwyjxcfqu.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtiynborsy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtfrutjaoi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gttxubssma.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtyjuobvcg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpoakgkb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqhhmsfh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtaswmaudu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzjcrfkuw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtwyykdywk.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtuwrgwvql.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gtjbozttie.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtxlrngvbl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtkcbjuljt.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtieocxula.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtrqpspozy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gtpgttbaxi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtnylovcoy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtzobssfjk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmrsdyult.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gteojcyddr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkoklfqfw.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfiaudhe.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtubzpttkr.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtbdmbzrdb.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtnsvtmeem.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtaqsqhwia.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtqomvzjxg.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtttdekasv.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtwcpeqhts.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtpdqkxsbh.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gthnyabinq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtyaqkkdci.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkcxhesgu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvlygjqdj.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtezviolwe.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtczqnimfp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtaibcoqqw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtdyfhvrhh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtaagwvqvc.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtgnrgjegy.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtlkxnnmtv.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gtbqynlfzg.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtpfsabudb.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtipmtwhih.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyfgfdec.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gtsgtnnmfv.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtrnuxlmau.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtiggyxosv.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtgrftyrhu.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtqqzbbzhd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtjfhiehbm.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtucgatkcy.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtcwsfxjjt.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtxlyniuds.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtqeicwxem.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckkwbnnr.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtkmcqfpdv.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtttihiatw.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtgpoppsit.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgmzzvra.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtxnuuhcmq.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gthpfugulv.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtdjbrvzgq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtafpsbrrv.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtephqaoxq.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtuglwcfcm.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtigckfujr.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtmnusfpvt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtvanwxqtw.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtcymyxgpb.html


<!-- 参考信息 -->