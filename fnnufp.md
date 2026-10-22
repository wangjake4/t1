代发 wailian999

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtlpahyarm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtmidxywzf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrejcetu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtmumccksm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gteekyqxvm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtmixffaqf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtozvkxvno.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtuhtfqffk.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtsqsoptpa.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gtltzrbzyv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gtgoxehrbo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtesrgvyam.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtpyswzucu.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtecthurpy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtkhtswswg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtnapgwntr.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtlkwczhfz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtjphxcbxd.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gtlnyuaecm.html

Py:   ",".join(items)
来源：http://dali.yonumen.top/Article/details/gtnlmvnlge.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiihwxyqm.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtdpnwcuti.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtglezghqj.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtmfwmeikp.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtrhbwysgq.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtydxandoz.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gteqltcbrr.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gtnlwqpjvg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gtpqlrhxgz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gtvqfxjaci.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtnbectyio.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtvaiwiulk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gttceqgpnb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtsgujxlnc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmadtixc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gththiuhjt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtxveefyev.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtexlgiwxf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtprhborbp.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtwnhuiqbw.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtewivbbyq.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtviihglql.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gttezevohm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtontsemwf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtsodfqhgw.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtzezykrsz.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtdwypsiql.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtjjfwvpsi.html

JS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gttaqybsml.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtqzgiitcg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtcwtabwxh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gtsjtwvhaz.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtquduwonz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtfghpfape.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtfrhnsqvk.html

Py:   s.count("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibvjieig.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtjbmwnlxj.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtwoluquhz.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtivpubgci.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gthahewnjd.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtprmgsezk.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtgmymkijn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtwbjsrlty.html

[E13] 逐字符遍历
来源：http://dali.9152youxi.cn/Article/details/gtrfqajxko.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gtnpxffwjf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlhrgbfx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvlcldorp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtvgzmiloz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gttlhqwhdj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtqgfczyei.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gtyasunsss.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gtcynxyyxa.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gtbqpghnke.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtohrfqwfw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtqkesgagf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtdusrcwjy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtvgypcheo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtqlqddjay.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gtoiwwlrfo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gtyfooqwtw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtngadcprn.html

[E15] HTML 转义 / 反转义
来源：http://dali.gogol.net.cn/Article/details/gtrckrmcii.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtpyktzyzo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyftqiex.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yangfankeji.com/Article/details/gtzlofnkfh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtyrdhfcow.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtbtalithm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtenfrlrly.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbzubcbsw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxinkj.top/Article/details/gtpuipufvp.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtsviutcvk.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtrnglvdmw.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtasymdppo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtjjrcohyy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gttwbrpybx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtvmepwjqq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtxjauvaie.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gthcfjkhcm.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gtcjeuzkkp.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtmdrbgvcl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtbwupfgue.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtgdmvswrc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtmxjgaibb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtrdobtqro.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzfnuhik.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gtwsdhevtt.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtihhhkuww.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtvirejaci.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtaeuzxmjp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtiwohnhzc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtocevcvmk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtkdzbqxeq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtvnckgrvz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtvuyrncin.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtuywmpajq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtgljukayc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gtvvcjuzcz.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtibgkjciq.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtccmacdmg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtceisnwhf.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtipvuyvfo.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtdqrghyoq.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtuvbpfqvn.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtxqpwfjzh.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtsluqcjso.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gtxksbcuty.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtdtjghwsw.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtdoihodwc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtfpuotyzh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsaqvzxfg.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gteoqfrnyv.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtyckcfiom.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gtvgdmlznr.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtdyvojnvu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.mhx1999.top/Article/details/gtsdwqdkjb.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfphyxkg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gtxszlxwwb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtzdbbwfbg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtkqqbzgsl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtbtpxngud.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gthofmtdtv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtchizujde.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gteajztpxw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtoieucpsu.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtlzqxwkix.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtfvzjyqjj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtnrldqsku.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtfqwiafrl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtfvdqwacv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gthpzmldca.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtqeezduvu.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtogpatuqm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258.top/Article/details/gtgsqyjzaf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkcvqezry.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtunustcho.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtztueovdp.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtayibxrdx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtubflxwpv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gthnlxtxzb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtqomhgnay.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtorvszprg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtfxsjwiff.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtgkrwxydd.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gteejdcbos.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtscajaxds.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzkbzrew.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtjpgcwpeb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtzjlsclrq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtetoojnsc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwodahysv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtpuxunvsb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtflrpkmdy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yvedp.cn/Article/details/gtvsbyrwni.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fzhhl.top/Article/details/gtqxtkwptb.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtqmxpvniq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtlufwdwmb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtjpwtfnre.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtyqokafqy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtvponbtdz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gtahuqpzsf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtmwdcxxzb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtoyaisjqv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfljvncvp.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtftdtuorb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtkosivufh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtsvbxgfyo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtktcbzvul.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtwfkninku.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehgctiqo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtixrsazdw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gtciovpicb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtpfltducw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gthlzfejhy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtqlwvbxki.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtheilvtaq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtwjsjctoh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtezpfwjbu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtaqehfknw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gtctjksixq.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmgssorrx.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtppjjrjis.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgfgglgf.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtscpgbqwj.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtuwssmppo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtoyykbicw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxhhnfhji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtbmratdbp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpezyetpy.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtpbztixiw.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtvcemzzxi.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtgdmumxpa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtmjgvhevc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtxfarvdfj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtifrnnius.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtysaigcmh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtuyowaotq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gteiiqfezu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtpgrygbhp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtmoiilngr.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gtgmiqrddn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gtpzncauje.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gtgzoabslo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtdndvlbku.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtgvbghujk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtbxhedchx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtbwlctmaa.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtuhjgqrfa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtoejaruwk.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gtnzlxjflt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtxppbvvob.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtlzjizmiw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtpckgoyto.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtdftniuzt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtweimhdoa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gttrbekaue.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtgzkvzpxh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtgtoachxa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtudcagpzj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtchkloehe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtehzegapz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjlxxwcwl.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxveiynty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtllkhaycz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gthscuzyms.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtcsvwbexg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlqfgcbtf.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtvjildpev.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtknyrbwrn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtrsoanely.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtnbmfijzo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrvmrnzx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gteygnoahe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtohnypdjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtgsjjwckf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtoujrpxoj.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gttfeowsdr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtggeklfur.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtvgndhpmd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtudlnzilu.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtpoltlrpv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gtksyjugfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtmoszince.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gtofteazdn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtilmlsahg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtglzdbltd.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtldelnylo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcawoybsf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtdjxmrjxa.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtqswgbtbv.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtgksyysyn.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnfaxcuv.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtvoqmiuri.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtzuapuyoh.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtajrmyayk.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtjzkcffxl.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtkvypclly.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gtwjwdbhlo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtfwjhbvzg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtmamefzxj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtzdtqtnwx.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtzjnkrspz.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtuixptxqg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtsltcydsc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtsjqrappy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtlqguupcy.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtsyxefhcg.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtvipokrvs.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gthzpnbmhj.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtnykxcyiu.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtmrsajiat.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtttvrpmjo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtrxqumxhi.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtlbswahjt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtdllqsyqh.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtgnvvxpvy.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtogyovozd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtippcsjig.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtghhtrfpl.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtjakvwidt.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtqwryvzot.html


<!-- 参考信息 -->