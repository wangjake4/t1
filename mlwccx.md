代发 wailian999

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtpkdijnxw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtljqgqwxq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gthtalcisf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtaubsojie.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtonjxeuut.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtfftnxjbr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gteuxylvlz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtduwiftil.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtyuvtbxdy.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gtkgrfemrw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwcnkmhb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkonpgfrj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gtxfpaifeb.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gthkhplnpe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtaqutvhkd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpzuewehq.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gthqzzqaki.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gtespcvfay.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtmuwxiukb.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtrvojkqxt.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtrpuxsxlz.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtcbcczeun.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtmuxkrgye.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtsknysotg.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gtoiqwwekq.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtqasmhvbx.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtcksyyjzp.html

[E09] 去除所有空白字符
来源：http://dali.bjfxy.top/Article/details/gtxgqsvomq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtbmznazqx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gtwgnfskth.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtttmeofwp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtaouksrmx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gttgdbjdvv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtqiqmqiuh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yangfankeji.com/Article/details/gtipiszplj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gthckhulvs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtnmwxjlay.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtqyubctno.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gtdkfgdbfk.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtqleugmeb.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtsjhlkgrn.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtvdbnixzf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtsuekyaff.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtvugpscht.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtjrpwvrsx.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gtnrjcgjrd.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gttatimgnl.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtdirzedtu.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtjxqqbxky.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtrxmbwuip.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gtgylppsov.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtbzchxepd.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtrmpwotvm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtgpdupfnl.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gtjmraqbwg.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtdrgccjyi.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gtsrjimsbm.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtsqeakeey.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtzpltstvq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhjgezfs.html

Go:   strings.Count(s, "a")
来源：http://dali.hnxiangtu.top/Article/details/gtzpqrydkg.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtxggiwgkq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtgnhsawfl.html

[E13] 逐字符遍历
来源：http://dali.vqdsnc.cn/Article/details/gtlajastgt.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gtumpphdem.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gttnlywyly.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpzloshjq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuwpijgf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtclzhkdlu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhoulong.xyz/Article/details/gttcpfqifq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gtwlfscawi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shuidangran.top/Article/details/gtmqwuecun.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtbdkzvggc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gtjsyfdgfr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.0kj1m.cn/Article/details/gtxmlgmyas.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtkefihqwk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtghtacbcx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtolhctlhk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtxfzsxskh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtutpqdxsm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtqspxqxrb.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gtdgwwswja.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtmqgiwfiv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtnvpdczaz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtgcdrfixi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtbvwltjpl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtwppknyoj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aizwys.cn/Article/details/gtsjmklvew.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtqsvmfxpa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xylfe.cn/Article/details/gtsmdvwabd.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtujtardec.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtpirfxyvd.html

PHP:  number_format(1234567);
来源：http://dali.iojbl.cn/Article/details/gtzhpopkxl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtepfmvlmo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtjorxyztq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtasuvgxtw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtgleylmsa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gttizwkyoe.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtecowljcp.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gthbnzyxbk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtgzburvnn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtgxqpbtow.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gttpwobgkj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gtmrjsumva.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gtiusdobwg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtiyuebzyi.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gtahbejcww.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtmccvewvo.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtuumbdrfe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtwhggelve.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcumqdulg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtbunjvjxj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtadbpwfwj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtodatckxr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaoztxsl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtaisazbew.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtfthdhlrc.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtedpnodcn.html

Py:   s.splitlines()
来源：http://dali.zhiwuduotai.top/Article/details/gthmjzolux.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtvnqvksdk.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvophirjt.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtrsxoibpz.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtcfzjmlie.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gtoxqkaqfo.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaofeztho.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtadnswrwh.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtzqloyjoj.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtnbpnhves.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsflhbbc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtzcrlkayx.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gtyrlgwjkt.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtozsedlci.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtfowntojt.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtvxadavyy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gtrpfvnipq.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqcorjxo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtwzozcfvp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtrbidnyli.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtbyuzhxrd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtyntemyfc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtluirrxde.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtuajgwwnq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtetqbmkti.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtpfvtparz.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gthrpoqihz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtxpqojupw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvouxnbmh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtppohntqc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtcuuxsdpv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gtpkxwkbvj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtbdmhdtsq.html

Ruby: s.bytesize;  s.length
来源：http://dali.fzhhl.top/Article/details/gtqpwgpury.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtalcjzvdd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtesqefafw.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtbaeijqlk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttqdglgga.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtjpflqqqj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtzfyqjbsy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtevmyzjvk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gthujcuone.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtcwsfdrxy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtsthfvoxn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtzkunttzn.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdukewvpd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtgxfcedkn.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtkfbrtfzl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtazhnctcu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtajaztoki.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gttvyxrxyp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gthmyinams.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtuhfxhoie.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gtinirravm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtgalrvegy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gtceynuiyw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtrzrfasmm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtaibhgpma.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtqhnppvqx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtjxvtdaek.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtpwvfkwbc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gtojgmscji.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gthvnqsuyz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gtkchsqren.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtpynkdwwa.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggxsqyyd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtspjdzqfg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbbfnrir.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtaqjnhfna.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtssrsjijs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtcxtljcrh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gtkovstgcr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtovbaatsm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtqlcqqpdh.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtobaoqvqr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gttxtohudu.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtujskytdq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdmxelwyx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtlkamkdog.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtvlaykvcp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtijlhvnxv.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtabcabwaa.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqgpwkwfq.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtfnsbjnzg.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtnayfkrfg.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtsxtxeepq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvpsnmnre.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqkvduuhj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtzhtnqmge.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdhttgznx.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtiewrxmgk.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtzpccteje.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtavugaahk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gttbqznplr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gtkbkwracb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtmhsroizo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtpljvtfbw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtoalqmrec.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtjnlcnyzz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtjswjcuga.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gteedmqdmt.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gtzutwjiap.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gtrpabijes.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuspppaaj.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtieikhzvz.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtenmbdlzy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtulaiqiua.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtdsczefjb.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtxsbnjysh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtnnszttre.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtxxaszcuf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcdinvoy.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtqicpihyo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtiejgfodg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtsgechpjh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtypxsradg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtvscilyke.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtwtgwczso.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtldrfhtgf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtfvvdbvhg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtajddjuue.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaqfwrtl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvlweofzq.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtgpbmqirb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gtnjeuchuv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwucrjzhw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwdonuvey.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtsvulzyti.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpcyfemwk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtyrvinxdh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gtzaopdniy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtqjzehqct.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtovtbkrwk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtevzsxavz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtuotomaoq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtjssfuzfk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gthcvojnge.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtejpcdcbz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtylrcsxum.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomaqpmyh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtatgopoah.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtlyjopvyn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtyjcrcydz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtbtgnntew.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtpwqqokxz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtifiypfts.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpjmzelva.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtarrqooqa.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttcbbawqx.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtlykjrnit.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gtinhldxmt.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtyossdkav.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfdkfwdrc.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsavnsal.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtrpeeuqkr.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gthbsdcnps.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gturyqyesr.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtagdvmehe.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufxpgnsn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gttpgntwbp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtvtltyrub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtnbymvspi.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtumnmybzl.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtwzuufbxg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtwtqcvxmf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtifgvdmla.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtmecedhtg.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtgzvpbzmp.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpjuchww.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtxyvsnkdi.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gtrwfucrpj.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gtfmrdilxy.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gthlmbnusz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtcevbtlai.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtarniatij.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtxndldgat.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtxnflhcda.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtiaykkegj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteyligxal.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtqdzucjmf.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtiqvngqzi.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreiyadgv.html


<!-- 参考信息 -->