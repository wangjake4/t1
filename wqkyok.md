代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtiovicvtd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gthjwardnp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hfpthk.cn/Article/details/gthkftsosn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtcdojaphm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gtyzwnvsms.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gtqatadrgn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gtkqaodhcf.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtpthzhewl.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gttkzlrnzp.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtalwbvrwh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtmjoyfvzi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtqlkhxjkc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtbjvvkjgu.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtxazqlonv.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtyipmcjdg.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtmjydssed.html

JS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtrxwgfjse.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtammztsqw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gtfadqkgea.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gtiuwlzxvw.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtwvffgxqg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtzrwdrexw.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gthxyfsfyv.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxsrotzf.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtshrhgpua.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtlqbzqicu.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtwybwziyr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gthqbzotqx.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gteytormsk.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtsiqolcnq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gthuiggxgi.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gtejxkigqz.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtvudljsrm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtutmpbhqe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gttksfvsws.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtczqkbisd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtcrwngbrp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gtmpuxitgl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtcjhawhtw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtmvdaotqd.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtxrcobyfw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtknuwtjei.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtyebuddxi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yongpay.top/Article/details/gtfzrwjzmc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzmozoee.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gthixunjdd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtaomiexxt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtmyqmeuuw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtqymnnqzf.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtnjimcitn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gttespkbtg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yanxiufei.cn/Article/details/gtclrllbsk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtvowrldbr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gthvsslvyl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtihtiwjzz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gtlpaofxpi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gtbebjsvsy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtqofgbrse.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtxzznklfk.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtvysisnnk.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdwvtedd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gthxltcvas.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtpmeztnct.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gthigaqtin.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtywbolndd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gthqfyshfk.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtfbcehygd.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtkgbmqgld.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtxwsnzdvp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigfzy.top/Article/details/gtxcfowkoa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtibdepwag.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtxatolmhr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gtxtfhwmkt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gtvyztklmf.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gtniwvpjwn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gtsihgaebi.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtenqmnvno.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoorutgr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtbsiavkmb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtrupkqsdx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtjsvgiltb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtltlzbgoo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtozjrgipx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gturbieroe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gtznwmqyfp.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gtdfegakuw.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gtcxouzehm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjczrklhe.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtuxtylrrw.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtesiipsxf.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtioksiwwm.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtmyoyzrcg.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtxpshrwqh.html

C#:   s.Split('\n')
来源：http://dali.c1oappe.top/Article/details/gtsytycjen.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtbsfrxgsh.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gtionslqez.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtfaekyvwy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtxuzkatoo.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtjsoembjf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtaljyqvrg.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gtidwuicif.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtlhkarmob.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtaiflphoc.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtqohrwqwd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkhvqogx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtdzmccmwr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtphhdfgwf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtifjrqqfs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtbdushxhz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gtjghxdtww.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtejrtlmgp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtqjuvlooc.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtmgbcmztj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gtlzsnbxkb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtzgfxleqz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtrlwtrrww.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtdegtmqnt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtenrngasa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gtjrnskmxs.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtojevxnys.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtmktyyudx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtweicuyke.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gtmkdozkwn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsplsaeha.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyuhcsjid.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtzwnjxynk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtlckddpbt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gtzjzuqiha.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtcttzrlvg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtxfkicjdi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtlczgqwdi.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtysmwypvk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtgvstsgmd.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gtilhtgeqf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gtmgtgwkyv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gtlwejbxie.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtbkiovrjn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtnwibpwvq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtajidugbf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gthpodrhso.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtknezzmbj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtixrbflfk.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtrkskmhlw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gtsipooxdw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtwuuyqahi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtdmgsjtnn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gttpmshhoh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclqzgncd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtzloynftg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtiwpvfsoa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gthivpjoix.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtduizzggp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtvynptpan.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtbzdjxecj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnryeqdu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtdnixcukh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtujsiopzs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gtyjywsgbq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtzjcvaynr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtchqyqtcr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtrwbkwkyl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtydaeraob.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnfafkloy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtntjymbxq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjjbjdoko.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtlelmrqew.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gtqzjsewml.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtfbsoowln.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbdhyaos.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtaklayakr.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtuapvzolc.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtkqtvfqqz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzgborpmo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcmnvueex.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtysaxpxxq.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtdhqbijdf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtryukmhjr.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtsrrjvayc.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtnpriowui.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtionppvoc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtstoiccgx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtccvynevm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtbgugwokw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtjxbklpoe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgriqnfc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtbhsjlwix.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnauxcikt.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtcjfjuvzl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoutyrrpn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtikbosqep.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtqgifhmqa.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtsmvgjmdq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtlqjlefdf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtjdfiwcri.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtgnvyneae.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtwuigzxrd.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtcxhmojfx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtfahhsqdi.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtoprlntau.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtjrvyekwx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtjtmcpfug.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtflshfxtv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtzwxwmnlb.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtygkzhdna.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtoinluesm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtrhvtocov.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtuikiobzw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtmugdkumo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtkcercbvk.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteasvsjzi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtylkdgnep.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtciqhcnsb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzcsfvggm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttmlvpcpq.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtwbczzjcp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxysaezww.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtfxbfidwl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtgmllbkwv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtecbnkfku.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtxwdsatcy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gtkohcvjkd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtylxhxbci.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtleybbkry.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtxbkljhsb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtqdqpoqsm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtmxiohvhc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtuyzqoixm.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gtghcwjrgi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtuorwafwp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtbcsqkymw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtrgvfysiw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtwtfrxtyj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxnlbbqbt.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtuiiojpgi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthwuwvner.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtememehci.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtysxyyrpb.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtywygmhnl.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbrauoiy.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtcxjqcchz.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtcvpbysld.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gtsbgifrfc.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtwszwrakm.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtojfmzcai.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtcrbkprgs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtlmaaeute.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtqrdvccnx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtqpgsizwh.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtffhjjydl.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtjozalrnn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtovajvyie.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtkoqnkmad.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gttcoogomf.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmadwjke.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpipalra.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtraxrjkzb.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gttbjpdavk.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtoyaspqzw.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtcebtgpat.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtqerampkf.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gtpcefeqxo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaepbstmn.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtepdfjihe.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtnlbgvogu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtylqybfnm.html

JS:   greet() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtsyzinven.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtujvmhidf.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtxafggzip.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtytbhqgrp.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtfmbhxxmo.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gtvkutyszz.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtuciylcks.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtddbtflrj.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtxzxvlbwx.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gttqmaohyb.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtdivubztq.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtfinpfnez.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtktxasnab.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtfratwuyu.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtiufpywtq.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtguxxeicb.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gttfyozpph.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtovsprsdw.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtbrxgbyji.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gttineephz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtjbhualpf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtbsngmjeu.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtcfrxiupw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtydobusim.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltiljafm.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtgbojwdnx.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtfsxtkvee.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtbkklxbcj.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtvxccipbd.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtmwmkmeva.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtysewwypj.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtyofqkpjr.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtpjwcvcbv.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtqywhxxpi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gtjbnzdrgh.html


<!-- 参考信息 -->