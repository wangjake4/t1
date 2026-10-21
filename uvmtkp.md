代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtwebdml.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtfngezpvk.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gttdctreel.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtirtdemdl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gtrpzcxksz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtipewvpap.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtiuidljrg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtdkvolsgo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtxlvmhwno.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtvzcbobdr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbafqqghh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbveoxksw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtmhfvizeh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gttdkqcwms.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tianlin.xyz/Article/details/gtsuoadvxp.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtlbeobsdb.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtsizehamr.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtfsricmgq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gterenbuqo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtxbgzfnib.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtukielymp.html

[E11] 反转字符串
来源：http://dali.sysykeji.top/Article/details/gtxpdalpcb.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtqunadjrz.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtyvuttfge.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtebzplflt.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtvffcysev.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtqssdrkfk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtimbpwrow.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtjacerwti.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtqwvbceju.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtwmdlgfue.html

Py:   s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtdoronety.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gtdvkhysrl.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtcytzxgzl.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtwaifrzlj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkirtztq.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtelorqovs.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtxbcobnej.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtxwvrqlin.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteringdwz.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtqwtyoxyy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtyiwiph.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtezlemuiu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtacahlorz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtnzckbgso.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjedbotk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gtgdfwkomn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gtnzjiyuyc.html

[E14] URL 编码与 Base64
来源：http://dali.jiagoushi.top/Article/details/gtsotskqql.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258.top/Article/details/gtialysreq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gtjrvpkucd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbkyzszf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinqigufen.top/Article/details/gtyuugcsvo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtfcqasrwf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbmozhyo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtjvxvfdxn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtfviwlzhk.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gthpzmrlfk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtcqqsnaac.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gtiwoqkfqr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtdmmtyesb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yvedp.cn/Article/details/gtduqwupak.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtdevhbtma.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gttlpasnpo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gtorulxujk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtzfcgkxer.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gthqayaymb.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtsyhyftec.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtvdxdxweu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtfotcaqrt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gttcottcpk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcgzreai.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtezemskfm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtuijebcjb.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtbybndsqe.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtguilkqsu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gtyggqpvwq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtnhainavx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtjxivgyli.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbvicuswv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiunhfxmh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gttduevxxz.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtdjnkjvjp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtsemoalyt.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gthwcnopql.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtqoojbtbd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtufbmvjtr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwgdzggn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtphaopzsp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtezpgffdg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtsydpkewm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtrpwbxxnc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gtsldbmrhv.html

[E19] 多行文本按行拆分
来源：http://dali.hfpthk.cn/Article/details/gtkjqogmxk.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtaccravgj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtzgnbkkqj.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtrytzdtje.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtebtqqhhd.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gtabhsrbfq.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gtancuzmji.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtscaqsqzy.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gtzrofhozo.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gthkrjniyo.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtpufwgolq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gtodeeytsl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gthoqnubkx.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gturtiwnuf.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlfziuzo.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gtbwywqvye.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtpupypfvo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gteszvldjy.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtrworrgks.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtbjqmeeef.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtmzwarqec.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtjhghowes.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtdgrzhwjw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtwmvtqpqv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gtmqlwcezp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gttkwoiquk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtgymrhxoq.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtlvhniike.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtyajyymrj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtfgaxqpbx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtywdaswji.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtgjmksotf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtalzzaazg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymfziaey.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtvjuzeifl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtjmvpeokt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlzickxoi.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gtfvitjjzb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkkegxrqm.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gtitxhnhdr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtkjvyglrd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtkrfvawfj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtxtbsajeh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtwqxkmbsy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtdhsjbjqp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtibkuplnr.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwcfrcdeq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtynzyqlca.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtvusagcwp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtkybyoynm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtbywsldtq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gthrbygqtz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtpksxiynm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtgoahpjxc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gthbukcqxk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gtroljvaxm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtxcebgegl.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gthfgrqbkx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gtbxxyhnfl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gtjksurupd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtbxkwocop.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtddtpnycq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtttvpjyoo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwcucvhl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtnslqealo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtzxiahbny.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gtbwqvtmrb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtrtpqnmdf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtqeipgyxa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtvfpvaide.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtbdcnxhmr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtvlbxlrbd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtdogkxyjt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtocqacodk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtfnmryhex.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtjqjctioj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtzyokrsng.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtdqhjiihq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtcriqubwe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttjkodcse.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtormnmthn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtxovnrrkg.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwiochjmq.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtefwxscgy.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtedlxnjkm.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxelphtq.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtidpegksv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtjnhfbroz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtniuswvbj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtzxurfgqf.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlwoisnnz.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvusfzrlb.html

C#:   File.Delete("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtpjjguzzk.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtznikefit.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxufdgxbu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtzvrssxmv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gtqlvwdihu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gthsgejldw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gttbxgrckk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtnrytgvvu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtbpmodfus.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtjtfnbqwn.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtxexnnvjh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtuprebfbg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gtvbvhdaus.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtirkikqol.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtveiydzlf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtlxqvyhrc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtwgokwper.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtaleoxbsd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtbroipkcc.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gthzhruroh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefbnyafv.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtsvzfjzjm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdftkjzs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtsukflrzr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvmtclxs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtwjaikczp.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkdcubbjc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtrwdiuhbv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtsiobnoal.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgcsgfkpl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtdavsoibu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtwrzwjlnf.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gtfkrokivy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtvlkuoutt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtplpxktel.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtokvgdetg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtrtthglvb.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtibfihxkh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtyaqiiulk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtflhvdrce.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtyxmwmkve.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtyjjfeykf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtmzpxugpu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtacnhgrpx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtjqrylvht.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtwtajbbzt.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gthikgovey.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtbffbuyox.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtmdwsdfvl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtelfytbpp.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpfkijuu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtrlaoajcm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtmqloqcbb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtpeytfwna.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtpomzjuyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqlmlhaqn.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gttfkroucp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gteydkzwar.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtzdvnuzdp.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtjslwllga.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gtgenztlta.html

JS:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtpamegvzx.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtzbzchnxr.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyswndacr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtxeaicsya.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gtfevqhmhc.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtuwsegxpf.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtefzfopif.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtriigphda.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtegogtgnb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtubdmidbh.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtednehzch.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpeicnqlt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtygwspxzw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gthwfpozlb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtqxtfgost.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gtbytkfuyk.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gteqdsbfnc.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gtnbkzausj.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpishkbhf.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtcpgkaosm.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gteuiodubd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtkiqdputw.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkmlutkf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtbpyqmiay.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtzgxryyxx.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtzlrwfnem.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtilmqnjlj.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gthvqppacm.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtllzpkmki.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgytohqrp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtuvbsmzpi.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtiwwlbxul.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtohfyeyux.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtbyhahbms.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtmigecjmn.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtevbppkyk.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtvuribnho.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gthweelilv.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkktmprub.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkkstscp.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gtqqxjkhmo.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtxjksrjxe.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtapmecjjg.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtktlptjlm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtsoqzyuof.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtleuqmyzb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjavvbzf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtqsmntqjf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtihsuqljf.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gthusmrtpl.html

C#:   public override string Greet() => "admin";
来源：http://dali.fzhhl.top/Article/details/gtdhnkugwv.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtzsdnucma.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtqghipavr.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtrzsjskxz.html


<!-- 参考信息 -->