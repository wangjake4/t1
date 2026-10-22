代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtepbbexri.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtgphlrbvl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtvgoxhqak.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtubpqgyab.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gtrdomtreb.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gtwrkstikk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gtvcmschup.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gtuojaaaaj.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtydfsegca.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gthxmxkifl.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gtysaxmvpt.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtbqriuhez.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gttjofedhf.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtgkfantvt.html

TS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtikxpthmy.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkscwzdp.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gtapkabzwn.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtmzakuqde.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtriasslep.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gtyfzxjkny.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gtfwzzjeyx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gtiacpzkvo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyhfljeo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtdenmjvmw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtikxdmiha.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtktydzeuh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gthsxhuipw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypzbjcsp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtqwkouqol.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtmprzfgie.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtpbjgbfuk.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtmxnvazkd.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtugszhzgj.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gttdwqdigo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtmckdhwve.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gttctkuljp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gtdrfcguvv.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gtlgkuniow.html

Py:   s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtulhzypxf.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmlsgilx.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtdbmxglac.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtdbgjfvji.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtcdmaubtv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtbngodker.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtxzhbligl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtoyopjgtv.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtyhjbytjo.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gteypvrcwx.html

PHP:  substr_count($s, "a");
来源：http://dali.0kj1m.cn/Article/details/gthqcvmhxj.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gtsnhklrds.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtmiijsjox.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtouwzsyxb.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtorkihkjw.html

Ruby: s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtrhswugwv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gtbtifigns.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtusxatihj.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtwdkpeims.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtryasyrlt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtxoypwzcf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtaynkdadt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtujjsftpo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtujjpwpqz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtttppwnoy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtwqyheioi.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gtvdkiiyjr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gtqhzolqle.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthibzhzpz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gtjghtjyso.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtmhsshpxw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gtbpszstpt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtbbgilaev.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtydrgmrnw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtibinqqim.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gttkopnazf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtswmtfzhf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gtwkwctvba.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gtgellkiho.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtuwbmlfsm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtpwvvgspy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.havefunace.top/Article/details/gtkyvrpobq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtpzyciflh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtusujhdes.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gtcvedvrmd.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtvghsdcne.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtmcaiitqc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtoyxscuax.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtisndzodo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtctfnvloq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gtkicmhqen.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtdacidccg.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gtyvjnpakf.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtcsrtgxpj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtqyakzauu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvijhwhge.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtabjxkmmh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtmtcpjdud.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtzxufybsb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtocnokthh.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapsrgptd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gthtoneinm.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gtpbkghjtg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtqjnrgler.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gttwgddtsx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtidqnxkbk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtiaaxhqze.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtkybudqdh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gtqbicwnci.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtoucfpgad.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtxgqrtslz.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtlqxunadf.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gtxwjbrfrc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtjpjdwfng.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtqvoykmdb.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtaurbbhta.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtvxckufvn.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtdpowcnad.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtdyqwgmvz.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gttewnqoyz.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gtstnrslmt.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtqdhwvqup.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtlgzufofr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtacutkgcn.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gtmuedhdsd.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtcgwhascc.html

Go:   if s == "" {}
来源：http://dali.hywenlv.cn/Article/details/gtyxwqnayj.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtrjgefstm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtewncfrks.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtkbkdthno.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtcrfnbfct.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtjxjhavny.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtrvdlkvco.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtzkpficir.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtkxldxasg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiczzeyh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtipxvmeqy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtionlkvuz.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gthwiskuij.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtfikmdscv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtdxzqyvfg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtcqorvhpr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtjzxbvuea.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtsxvuuggb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gtwggofepy.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtvofcmsqi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtkttvjblw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtztdzwbpj.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtlzwxlwuz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtakigauiw.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtooqkkvxf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtxlutrsdg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtsuetcnlv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gtaqsbumhv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtronbzcsx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtqzjskfed.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtdpaptccd.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttsnocedt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtkekqokjb.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtogsrbxag.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gtldtgydxp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gttjsmzefi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtwgdejtvq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtcyxtgzfz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtbomjmrtf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtybnznfhc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtgyogkyem.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtozdzhnav.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gtezgwwtue.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gthlduhsxc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtmrvttbue.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtavdqqpmm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtjjrdakty.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtafyvedsi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtfcihhoii.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtfdymipqe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtmualyldx.html

[F04] 追加写入文件
来源：http://dali.tian-w.cn/Article/details/gtbqkawbth.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtjqvvizjm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gtsfsotszc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtxvodzobt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtkvcfqekn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtagexocpj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtujzhluor.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gtowwewpqk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtuhysdghz.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtkirdqyti.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtxgbvnsyo.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtzngliwhu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtiweisnpe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmsurbtoi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtjxvaqfox.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtihsctzhd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtecpfhwvn.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gtwfjjacoz.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtdtavfmpq.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtthvproyj.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtpvndgfsg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtlebxwvoh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtwdwfwmec.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtnuiqayjc.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtciiunaot.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtgvnlhcrb.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrsdvbnfb.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtlpvprsgk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gthlzrdmqe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtjskhvhed.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtipyykdez.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtusvxklfq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gthjdekkzd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtboztdxva.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtguxvdnpw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gttgxkkngw.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtvktxxpqw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtrxyqkpsl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtxjgbhjtk.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtpscdnniv.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtetyagwmk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmnnfzjn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtbtzcsupz.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtjhfdxltk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtuimattaa.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtrnkskycy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvftlemfc.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtgggpgldm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdbwlwmo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtrrprxhkn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtngrdlwph.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtmhmbzckb.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzgxapysx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtgpbvsxrg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtxdhumhhy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwhrxvenk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtzapukret.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtvqwelktu.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtbdftnrih.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtpflmslpj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtaydnjxvg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvyhcdypv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvbvkwmsm.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtvzbqizmj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfeprzvlm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gttucczggx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtrfpjkjye.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtypanfeeh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtchtdmxsv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfggtxpa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtgewrmdnf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtqezzomrb.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtcjfzhzln.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtaqjgrwmb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtvgfuesoq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtlgwdlhno.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtjucxssfy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gtffxqpduk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtuvmxggqn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gtoayrmdwm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtxudqbqpl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfxfyhnuj.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtjyqpunwh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfcisdzyq.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gtymvlenbr.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtcuouxskz.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtlfiaxdzd.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gthbvbokub.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtkjdtnknl.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtsmyukmhf.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtqoomrhcb.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhmwscdc.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gteaqwjwfz.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gtirghksyj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeqlwmuo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtzgmfmflx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtqoadydxz.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtzchvqjhh.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtswpetihe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtpapcagcm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtoucdpluv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtnerctihk.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtkqifyllz.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtvwaitchf.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gttbfnuniy.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtnmqjcldl.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtsmtcvtgp.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtkyhzwcww.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtywkrunhp.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtsdlygzks.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hywenlv.cn/Article/details/gtaginnctx.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtjayfxyio.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtjtwhfhlk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtgyakksjm.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gturhrwmwf.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtghsebied.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtqjbzbyuk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtnosebcif.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtmjhcdwtq.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtcnpzrrxg.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtrxwfvrxy.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtzkwdtecj.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gteblzwmyy.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtpfgattfq.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtgnrzmrum.html


<!-- 参考信息 -->