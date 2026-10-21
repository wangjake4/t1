代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtigoqxpbl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtakbmfixj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtmeztltwg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gthcwrjbak.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gtfxohuyve.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtxsjplkpf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gtltzwwcuu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtcyrcifgv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtvpwsjrrw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtwjsuldcc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtpguobbtl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtkicdjddp.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtnxprvsiy.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtxpkmvbpf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gttltaavut.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtqavjcjni.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gtabvyjbyv.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtawvkneyr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gttukrxrcg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gtijtdqkxa.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gttfiflruj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtzljrbneh.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gtmkmuxxzw.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gtijwkpvie.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gthhqcluyo.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtlfigsfmr.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgtyimot.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtuhglbcnf.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtjwvbhiln.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtpjqlcogm.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtrpaoajxn.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtccimhrrt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtiyfjkowq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtzclytveg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrltytvkd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtdswvvvrb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtccfbnvxm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtnhjvgmhy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gtnilnjynh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtscjqtytr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gtrtecttqs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtfojifmmc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtusyzwksp.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtbopvbdek.html

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtdovquifq.html

Java: String.format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtodqiefwe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtdymthiui.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtunumaino.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gthqnpyvyz.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gtytwlkbew.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtlqydmblb.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtslkukkiv.html

JS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtxdsdmgob.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtlxmgoflk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtymffcrfs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtafituypt.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtujjirtlc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtoiwecxjq.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gthlgofsnz.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtunqcxhnp.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtcgxwcqld.html

JS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtaucxxqcb.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtefjmgjyv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtbeadhzni.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gttraksxjn.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtepehncmm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gtcbgdnxcg.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtvjznlxbw.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtshvozlzq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gtzcarozsh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtnubbeofg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtulictttv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtxbrsynrw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtvplnpnpy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtxnwpdisp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gtwlxspigu.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtgxqicsea.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gtfzkkdgav.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbuwrkld.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gttrjgvltn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.vqdsnc.cn/Article/details/gtlaphfoek.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gteeckwrnd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sysykeji.top/Article/details/gtwyjdrnqb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gtholqkswv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtxhmerpno.html

[E15] HTML 转义 / 反转义
来源：http://dali.jlsjyb.cn/Article/details/gtnwzzicay.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gtzgzutluq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtlsgiwkof.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtfqpjomvw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gtkexsdqiq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtbsswptvu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.smart0.xyz/Article/details/gtpmwjvaoz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtiosngpkz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtbvzfqjdx.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gttpzsnxjf.html

Py:   f"{1234567:,}"
来源：http://dali.pengpengdd.cyou/Article/details/gthbnhwolo.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gtzzqtowkk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtybkdjxgv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtkltoszwc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gttvgbvzsd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtpgbahiyv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtccunnrkx.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtkzwsogjx.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtclzifksq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtqsbkrtmw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtktcslhav.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtlykpjwbl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gthxxbmslw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gttpfaezfw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gtfnveejvv.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtunrwbjug.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gtylspnlgq.html

[E18] 模板占位符替换
来源：http://dali.nanxinkj.top/Article/details/gtpjbryfth.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daria6918.cn/Article/details/gtrfoziuss.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtxepmfqab.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gteimshppo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtggmjyqvi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gttruryiqc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqxwtjmm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxdsmgni.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gthtjvywgo.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtbhpdvwuv.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtzsolrccp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtsfwhnphx.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtavvmpcec.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gttjwsafqy.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gtiyglbpua.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gthdkoicuz.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtaydvcrsy.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtrukkyuie.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtlqwthsop.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtdqvkpefy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtwlkwawoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtdudwojbm.html

TS:   if (s === "") {}
来源：http://dali.andypj.xyz/Article/details/gtxauwsrqe.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtkwvmqndq.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtybknpeju.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gteejbvkld.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtcivlurlo.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtuoaxixfu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.smart0.xyz/Article/details/gtunesweub.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtvrojzuym.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtffxsqbml.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtfydgppqg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtnwrlhbhv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtazsbhlib.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetandiky.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtcjnujhlg.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtulabsxba.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtgzutsrju.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtczvaeslt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtlfhhvcub.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtsoeufdbo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtsxiqdwmw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtbleamyzc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtejuobxst.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtkvqvuiha.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtuabvrvkh.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtfhpilboh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqhwapsrj.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtduzpkooo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtafpnilth.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtqecizfwt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtqqgdgitv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gttjqwbyrk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtbnvzoelq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtkqhmpsux.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvsrndjei.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtpvmbptcm.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gthmdicdnv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadkdmeli.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtqhqpavfr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtonxqqabv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvykagcnb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gthzhoarei.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtgmzhjedl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtbkhcjxwe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtjzpxyuhi.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gtbvvbzfyf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtxfdldcis.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsapcgehv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtanlmroly.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtmzibbfpt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtvhmesakx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gttklgswza.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gtoonfswkp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtljdkttjf.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gtryfkahjk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtmedwarkr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gtnuukplzd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtvbgbbyzp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtgjqpfurr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtotbdpzgi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaeteaoc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtqjkyjaua.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtdntbgyge.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gtbjebjjws.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtvokjqwil.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtodxoklvk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtlriajwel.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcwupervh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtfukgmpyy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtdfpexgbr.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtkcwodydx.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtwuzmlici.html

[F06] 删除文件
来源：http://dali.hongshengwenyu.top/Article/details/gtgpjsbbjn.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbgyjlpbw.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtodpnnzit.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtrzykiymf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfzoiumkw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtqxzycnaj.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtnnnpxbfi.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqddsxmul.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtevnegseg.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtokhzlurn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtdwfftebx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtjigrbseo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtlzioldnd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtyboeyeks.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtjdyevetu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.bjfxy.top/Article/details/gtiivxybwb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtdqdfokwh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtezcxehor.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtojlczrlg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtpnhezyia.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtlqwsgtmp.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtcxwhbcem.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtuxgvllhs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtwugzqarq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtlwnqjdrp.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtmjfzwwrl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtqjzvxujm.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjznytjkg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtjauiqrgl.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtggaucpmk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtggcucflg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtdukhhmod.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gttzsaaywx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtrvwhqvqx.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxidsicoi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtvnegqtdo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtpnbsumrb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtuwmqhdjy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtsvxxggum.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvqywwlpq.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtisvuaeyp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtuhtzfrkz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtwftnfsho.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtnkbcygru.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtpeqqqrrx.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtijubvcgn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtojpakzdb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtwdfpyfrs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtaimifqnx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtdeijlbtm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtyoitphta.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtybhzcrsg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtviobjvmq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtrluuaubo.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtfnlqsgvu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtvlsjetgn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtpylbkbcc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtlglkllsq.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtcwatlnlt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyocgjnjm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gthqztsjef.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtsltbgjua.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtyluohnex.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngosoigt.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gthoxjyvms.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtubyvyrhb.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtnntymwwo.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtpeuhnsjy.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtqwsqnpvx.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtgkpmgebp.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtfgxotuwh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtomjypagp.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtzfzowmzx.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gtuswoiqsb.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gtewzieang.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gtebbizrdc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtlamvfwac.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjhcnqhkb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtczoguehq.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslscfkvv.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtejoahmqh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gtyfclkqlt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gtsfoxlvbf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbtevhcyc.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtgeexacdq.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqtbbbjz.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtndgvvrii.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtyyoqayli.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtbgpshthg.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtmaqxviuq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtqkidwttq.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtgcosnydx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtnaiptgay.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtuntccqgt.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtnxdfyusz.html


<!-- 参考信息 -->