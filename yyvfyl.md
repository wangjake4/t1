代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gtjgediyph.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ivvv.top/Article/details/gtjbsqbdbo.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtgvwmwmro.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gtzbdyrwpc.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtdioykrry.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtnkablxxb.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtykiebvpt.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtocoikvgs.html

Go:   strings.Join(items, ",")
来源：http://dali.xziqi.cn/Article/details/gttvkrzpno.html

Ruby: items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtpsrdzooq.html

C#:   string.Join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtmgxfimcx.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtegythccq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gtglksceys.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtlrmbeiau.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtimeoiwie.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtikgynwlb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtmhwxxfbo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gtievhsamq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtqckmwsmw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gthspnhiyi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gtisklheja.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtzctlfoyh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gthkhulean.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtkmaevfne.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtviahipql.html

Java: String.format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtnecjzgpo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtgheojhym.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtrkmzrgnd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gtzvurkofi.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtykvbhmjd.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gticaurgkw.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtctsoxakr.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtsyrijayr.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtibwigcvb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.meibo888.top/Article/details/gtghpsaqrk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtahsiuqjz.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtwneweafa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtjjmteshs.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtxcmxzswe.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtdwldcggv.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtshlborsf.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtgscmnnrr.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtniwmmzdv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtdxdmogrn.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gtwgmilapx.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtdgekluyd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gtvwbvbgii.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtqqcjofic.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gtokohoyqq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtduyrqwwp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtufxdoahz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfyteswf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtsyngpxuo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtgbdjwiyi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtzaickoyb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdfvicxm.html

[E14] URL 编码与 Base64
来源：http://dali.haohaochexian.top/Article/details/gtwyhdgvep.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shuidangran.top/Article/details/gtauhkwbjy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jianghu66.top/Article/details/gtrtgaqljy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtiohntlti.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtyxkfrcdo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtjhvupqwv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtaebgbvaq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtdftpbmcx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtrhswsopy.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglisyasx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gtugpdylqy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guowangkeji.top/Article/details/gtypzejsoc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtlbwvccwh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtcrqasggf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gtshpohnfk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtjkjzpeyu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtukaqtdqy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zycfv.cn/Article/details/gtyhxxbqyd.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqijmevr.html

Py:   f"{1234567:,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtgmxkqnda.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtlqxklzzl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtyqclkigt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtenezucvh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnyoiwwb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtyfyqtqdj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtwsizvgsz.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtbsovicom.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtburjxrsp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gthmwtsfbc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtcooyfqkq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtpmxudkfp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtoyfjmkat.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtkxieoqqt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtqfehczdi.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtcjcwtpfu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtphkbrwlj.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gtgfdoudbg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtumfyttgc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtrgtnedjk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtqlhasuug.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtpqidnvac.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtwmikjqyn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gthupvjcre.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtlznuwtrm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtxqknuvsp.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtzbfwelnt.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtkgrgdjnv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtookvowqz.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtbmbdwfde.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gttqbvmcbu.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtcrcvsmgp.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gtoanqgluc.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtolenwfsy.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtzxjtigic.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtoqclccsd.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtibdafhmc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtoocsmfrb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gthwiuncax.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtenuqtnxl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gthasdshvp.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gtkikqysej.html

Ruby: if s.empty?
来源：http://dali.bjfxy.top/Article/details/gtzcygktmu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtstwkpkwj.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gtxyhdbyag.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gthovnouzt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtzyhkhhev.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtrshokyeq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtqvkfxfbp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtaqxzodda.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatjeieuw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtbkezdqlo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtsatnzxgk.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtkmntmfdn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gthpnifrym.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtguxncfmr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtltlyuwty.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtacqzaevz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtozgkmsrq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fzhhl.top/Article/details/gtnztorivt.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtllntzvnc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtorimbpmn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdzeyhjgi.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gtquqnybqs.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwretwtub.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtcxkufaov.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtsgxbkuzz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtbdeghmob.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gtzxedeehd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtplvwesvq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtxgorrvtr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtgwqyxqlr.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtdqmoswqu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtisuolsbm.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtzehkwycr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtgahjnbsv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gtneyjjpel.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtcvacxthd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtwnmrcduo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtdbehrsol.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtpujlawmz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtaeklnbsv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtkeatwbzm.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtdjptvdct.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcncoatm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtwbtibskm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtampuursy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtagzyxnxq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtmiwvxqsy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtlcdoexqa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtkqnkvqse.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtngxjgilt.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gtdatutwkp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtbxorittz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtbhomjoiq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtbajbiicc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtyqtkfwmk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtrdldwuoe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzoitwhur.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtprrineav.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtzgtazqam.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtezmqtqsr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gtdyyftvfo.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gttaydzlvh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjwkkapli.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtacoecmha.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtktoqhqtv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gtocsmumgh.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzlgtolyx.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtjfbqlsvr.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtwecsogjs.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtyfnyovcf.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtebgtasbw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtyjmmzrji.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfirlhoqz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtjymekchh.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtuznuxhpe.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzuisyzpq.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtsghwkruq.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtdtqqhpms.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gteuvqpivj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gtolsyibor.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtlxzsqwda.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtqecjphwy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtuiaqxoad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtumiyfqdp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gteaftrshf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtvvzpgvue.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtaxmkryvw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtkeouwocx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgndfuni.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gthqgvdgmg.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtsoctmzwk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtpbdtgoan.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtnphfflaz.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtemlojqvp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gtinbwdiqg.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtlerrervq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzermmfou.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtgwwqcihn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtdgxuivlc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtbgkjbuzk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtphznnuhd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gttqvjicer.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtilsnohql.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtxmalbfxg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgtkqwxw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmxyrjzll.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrcgaknq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtsjvnsxvi.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtajsdefpd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtoqjppgse.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtorysuocf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtebmdbkvx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gttqqarejk.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtegcbmrkt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtxinzqhba.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtwvqpqgbm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbwqdlixm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtswddzmuw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtvemxyfyq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcahhzzb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtchsrimti.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtepqunmwl.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtmaoomvfc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtmlcegorc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtxupwzike.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtfddjdfsq.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtglfvjhhm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gtjmrcchrm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtsmgffcjr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtipogadqv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtmcuixbmv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjkrblfhz.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gthbqncfrf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbeftgpaz.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtvfjdcfqi.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gtnmzyjigl.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtjnzfrnnv.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtodbsqwkt.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtytrzwgxk.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgutkivi.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtqlvpbczm.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtdjfvszsi.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtogvhsnvj.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtzfqbehcr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gttupkmnra.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtkfgqfvia.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gthhiounld.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfvqvfriz.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtqmcfutar.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtekmndmqx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtdbefxuei.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtepxcpikm.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gtidsfpbju.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqihcolmu.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtcvvhxhet.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtexxippjc.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtfxnpqkmp.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepdrftny.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gtppihiuyq.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtetogwxnf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtzwqcwfpk.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtxejbckjr.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtzacvxzvv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gttnrocevu.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtyetzaqjn.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtvfkawcek.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtepbvufkj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtbhqqjfsj.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtkxiwhpdj.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtrctcvxte.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtvjhgkrar.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gtzbynhfcx.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtxzginvoe.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtoavhfiwx.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtrutbhods.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtaskuxccn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gturrefhrt.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtvepirabq.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtzhsmbdmj.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtzbvzadwr.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgrcqbvl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfmdqftu.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtgvrspqkk.html


<!-- 参考信息 -->