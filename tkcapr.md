代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtlvisznju.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuanzhike.top/Article/details/gtftvcztko.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gtvglhbuzi.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtrrdktzkh.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtwngqlhuo.html

JS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtgfcivxew.html

TS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtorrcvakm.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtrgxrfvvk.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gtqflvkvuo.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtwwdswhky.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtuwlavmrr.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gtjeehhjcj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gthqqlppiw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gterlfpgkm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtcvuzuuny.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbojivkag.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtcxbybeif.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.iojbl.cn/Article/details/gtqlpemvtz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtwqtiyhiz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtvlqafiwi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtxujjhxnu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtixkcteja.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtfybbojob.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtekaxkqrk.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtcooljfwa.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtsgwjqdvz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtrqlpbhaj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtrlkihxke.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxstwxhv.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtakebjdpv.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtazoxltoe.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtvmsnkmoo.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtiqhlcaor.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtaabrvxlc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gtlefqcprs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gtzkrlbqhk.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtzodxwung.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtofgdosnn.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gtgxcxefvc.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtqrrcswbl.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtapyybtui.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtlodhncxu.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtaykakqtb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jianghu66.top/Article/details/gtlilytons.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gtanjptojc.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtmesjutuq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gtsujykuya.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtltmnmkta.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtgasqpapj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtnnufkhtj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtmuuldeub.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpbaxzqgw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzvuoolrm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtuildjezs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gtbpakjepo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gttsgtyiaq.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtxxjxczke.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gtolnygrdi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gthwrvwcqh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gthkfadsfg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtstqqmbzt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtnvozhvty.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.snrcjt.cn/Article/details/gtldnykhbp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtrxnjmjmh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtmgwetpey.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gthwxypctq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gtjkzycvco.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtkkqaiwgr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtznslqqgj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gtbbonpmeq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtgtzfgfwc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gtpiqmobcz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtjemkpsfr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gtqewwogyv.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gtclevhrte.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gtcuxcgybq.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtrkrrilpu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gttofiigaa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtixbwbgvs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtjujdniyp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258.top/Article/details/gtctxfdmmg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtwnxqixfd.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gttfrarsfj.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtvuzbgjzy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gtkphxojso.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nwbrower.top/Article/details/gtbgtellvo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtdwaaxzme.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtwswfcgdr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtoiclhxsc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gthnluaycl.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtthfbbhzs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtphwhulpb.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtjewjntpx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtxcdhmtgm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtyafbavke.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtmkrpbhcc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gttxovqdpv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocowzilv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqujtuns.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gtpthxsipo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtoedexrzx.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtzcupvzaz.html

Py:   s.splitlines()
来源：http://dali.jyoumei.cn/Article/details/gthcmefgck.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtbyzzqxhn.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtcdiwwvyg.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtcwzaqmpz.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtogcbxrxk.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtjqxpcnzy.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtczlnrfni.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gteflyqfar.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtlmswxias.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtsfycjqdn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtpsfzlgmd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtontdqfhi.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtsrkaernr.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gthtoxjipp.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtossrkwcm.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtuwewhtsq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtfuhalaes.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtkdefimzv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtxqjudlew.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtotcnpzjg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtndyiasmk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtzzafnnwk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtodrrmfsa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtetqtiinu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtxwtqpwkv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtdfbyrdju.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtzyialhdj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtgxaoyoxa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtxgkerxzz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtjpjtnqyq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtveadctpp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gtrgqonjmb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgcsznqq.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtzzjogrli.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gtfpfyztcy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtofbweilp.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gtkvecumzn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtybfjredi.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gtnnzgptsk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtytytswai.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtzvfgvpjl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtkrgbhocg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtbkqvdfwd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtobuybpmc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtumiuavdd.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtzwwczdwe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtfgmcyqyt.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtmtsptcrz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gtgwrsjzsa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtnaracygg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrvisvhc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtlptvzroc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gttndpjcck.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtozpcledd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtmamrpyrq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtgjgdmdfl.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtjvzwqshk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtiraqfzvh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtcoogamfo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtxiffhcqd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtxvdceaeg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtzocqngvy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtihuwjemy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gthdppkvut.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtjbvmdrtz.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtcstfpbvg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtyrsujpyn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gthijtyzbv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnhkexog.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtsvnxeaqk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtusqopohx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gtsoaufsdv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sysykeji.top/Article/details/gtsdbgzxtb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkvdjrnh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtthbjmuje.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gthjzvdfvh.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpfsoznyf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtiapsicux.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjgvkxruz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtlwpulmsk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gtbvivtixc.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrehidqzg.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtgmctmupr.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gtcfxaaner.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gthtiydxja.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtgonlfcaq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtulrasvzk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtbxzjhtgi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtkuqdqvyi.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtmjctasoe.html

Ruby: File.delete("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsollfwzj.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtbwotjuue.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtpnvxotbh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtsmipzxwy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtmjtdryus.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gtloiyhotb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtkdfztaqq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtrfsljblw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtcpxgwnst.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtfwssitaf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtkyzvyvsd.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtrtmhsfgl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gthlujndaz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtglymkthk.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtlyqammjv.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtqvkpqhxb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdrewzlx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtujwzlycc.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtutuybpqd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtthxperdn.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtpjvcsvwm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtewhdcomu.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtdvqposnu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtfayisfsu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtunqkyudh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtwkjtiklm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtkxwpggya.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmdpishrk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtlagiqxdz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gthmactuoo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmgvisazz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gttmspegtt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdcynolaj.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtfxtmjtnm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtxgzdplzd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtutlwiutj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gthabkuaag.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthrmyyqzv.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtkwzuhdne.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtowdxdlsa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtxbwvuquq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlitguxsb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcvzwdagq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gttrfcgjhn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtduvbbccq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtyyufewap.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtjgzsayfb.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtlznhutwo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtdhfmjjtw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtbtnqbdil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtlfrkaaud.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtkunxltwd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnxkdgtw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtgsckeumn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gtclkzpvbb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtgrznyjlk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtystgnrmi.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtydvzhsqy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtuwkwoayl.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gtivadoruz.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gteihyfbhl.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtzvpomwih.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtdlikgfmf.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtmpbqplcp.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtjzpfajor.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtdlmydwdr.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtjafflngr.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtlqqrmmvs.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtjlapqqfy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxdeqtab.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngmsouik.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtntqdhpxm.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtxbgcsdcf.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtrenicvnr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtmwqpahym.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtgxarvefn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtsvuyyqsq.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtsobnvcxt.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gteezlffkr.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtvjcqqcob.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtznhklmlp.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtbehtcjpv.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gthirhxvvf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtzndsyrhh.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gthhgmtizh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtiwlyaadf.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtntigrpgb.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtdevtyqvc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtcqvzvhjk.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtumkolmgf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtpklzdavj.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtxvothnew.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtrcfybpdi.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglfrlkfj.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtawaqijvh.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtwrfkzykl.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtocoscvqy.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtclfnibui.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtxeoehfee.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlhrrdqhh.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtorqkwflg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtzciyaagh.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlttacdx.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtdtrxwilo.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtyjlpbykz.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtlejwatad.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtxeqncrxp.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtbibnzejr.html


<!-- 参考信息 -->