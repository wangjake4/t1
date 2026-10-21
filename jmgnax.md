代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtnxphggyg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtxmhtscqi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtbwdmozbc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtanzkrtlj.html

C#:   s.Replace("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtqmogcfrz.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtsrrmqeue.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gtittmohmr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtbvwogljo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyilgckuz.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gtecvhdixj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gtzxychevx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtnsyohzyj.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gtuoplobkx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtweavdhxr.html

[E08] 数组按分隔符合并
来源：http://dali.chenjidiqi.icu/Article/details/gtbnvwxccb.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtewuoxosi.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtvhjbdvft.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtkadnxwem.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtfraciphh.html

Java: String.join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtselzbond.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtuwtkbwtj.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtcrzqcnap.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gthyiefuqs.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtupbswfwg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnzyhxeqo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpwpepwz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtgklznoxa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtrbalweeo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtkovnlacy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtnaemcsjn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtcobpxkgs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtholqyexl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtnpshgbyj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtsvheslnm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtqbqelmyx.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtyhhyynjs.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtjdwitdxe.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtmbbpqihc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtjcvlukvb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtbvwaclcs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gtnsguphrx.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtoxxtkvid.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gtuihljhed.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtujvmgxxx.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtwgowkwjy.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtmqkkhyzu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gtvouhqnfc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtdvoomsqc.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gtlghlmggg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtczuzmzfd.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtsyrjblhn.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtuqefifir.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gtuounbzua.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtwoegjqpd.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtjqeqzlci.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gtpmmgbdeo.html

Go:   strings.Count(s, "a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwbiymnq.html

Ruby: s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtdqdntxjm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtbidryzld.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnnktbzg.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gtqlhekwro.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtvcswsekp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtkblnjtsp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtgtxcrijt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtjyxelgtv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gteiyautqg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtvqzhukid.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtnrgbzkpe.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gtcaoavouu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtxjhfbccb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gtewedqeed.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gtcnzgmrui.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gtqsfvcbcg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtxwnjegzk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtoqebmslm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtocofrqzl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gtewibsuuf.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gteeipyokq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtsmjvdyhb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hywenlv.cn/Article/details/gtgnmgnqxo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzyvrqnpc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtnonvwdgu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtnxpliyro.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtiwoykhap.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gtlbgbihwx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gtomktwfpi.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtptrmbzzm.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxbldbxt.html

PHP:  number_format(1234567);
来源：http://dali.yanxiufei.cn/Article/details/gtpqrxqthj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gtkuvkkzyk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgztjinka.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gthkxppbbh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtjhbfpbhx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtkwioitgg.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gtjimobpsj.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtpzxsddrw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtqqdjsmka.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gtgrcyqabd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtevaqnfqj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtptvvufjx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtdtbhxyvn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtabdkmrcd.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtxfnspukd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.birdmap.top/Article/details/gtdflzauvj.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtntpmbmdg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtzhhwrrok.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gtaeiihfgf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtfnwgjrae.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtpisewegs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtdqmiasjr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowkcwbwl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtnuubjigp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtlzwsoaqu.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtkjcbzmsm.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtqikphgxb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtxtfcymkr.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtjszfnzza.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtnxpyeqqq.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gtphhqecbq.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtdgpwquna.html

Ruby: s.lines
来源：http://dali.jqgfzy.top/Article/details/gtnkrhmidl.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gttyqyewds.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gttlryreqd.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtsumbplqd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtwfpybkcm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujtawtvf.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtsxxusxcz.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtclgmfjnr.html

Go:   if s == "" {}
来源：http://dali.andypj.xyz/Article/details/gtqnisqdvo.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtzlimzyde.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtssvsonzo.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtyzbypsoi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gtsysaaojd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gttoiprbqb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtmiexzyqj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtrwdkgziu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtvdswihux.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtsdrvkbsv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtbooridti.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gttkzxxlit.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtoungwueu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtevijilhw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtjrdwrbgy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtkxasoddk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtilqahzfh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtamlkshry.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtoqxpmvjp.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gthjxmfmsi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtewzszetp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtujtuqrhe.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gtejtivpai.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgpdlznje.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtmknqtpob.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtmhsunwul.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtvfpytpgc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtptgsiedu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtdvuieivu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtaoedqwgs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtxfjdvyfo.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtgqcnxvnt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtlsqxvdec.html

[F02] 逐行读取文件
来源：http://dali.tanke756.top/Article/details/gtclvzdvkr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtetfijard.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gtcdnuwkry.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtsrphddcy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfusddngw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtpvxujpzw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmclmiqq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtdmhikids.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtuigdojep.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybmkjwal.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsnlofxl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtmgayjmdz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtggiyizpe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtjjjfeiiw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gtvzghmglt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtqvhdaxhx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtaozzrhcq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gthjlpqqrx.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gtrkfcbsof.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtkjthnvkg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtaahfmucf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtlfifyusl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtznrfipjh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtejhubeph.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtsjvecmxw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsqsvzmd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtvdpivyjr.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtztwaluij.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtntspaosl.html

PHP:  file_exists("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtiwbmunmg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdgzvpkcf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjaayigce.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtjdevdfqf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtomarwwde.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnatluxpr.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnqhbebhr.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtijgryizp.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtlgoqqxqi.html

PHP:  unlink("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtoovmnjzh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgysyflmp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtpxpyrxtk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtirtwqyph.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrougnihq.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtqksulyfu.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimjuquqm.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtauyedyia.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtedenafaf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtsgbwfwpi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtohhechas.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gttlpvtcou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtnnsbjknu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtvvqlbglo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtpifuwqeu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtyjkxxznq.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gttheudlwc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtkzcqusmq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtaonnom.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtwreewnnz.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfqqrcly.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtdoymtwqb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtywbdkies.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtbzbrgnjp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtfpxkqooj.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtcogezhmq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxsoyytlu.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtjgqydmbr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtgweanlcr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtbcwbgodc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtnpwvzebb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtbszjrydk.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbdlbmhja.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrkrazkz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtduhmiohl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtpfmcxcau.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtmeddnzwx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuyeipdmf.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtnvjqfaig.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtgbuxfqvd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtywavjjuz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdaumtmdg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtcoejedan.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gtapkjpsic.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtmtkicfiw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gtxztopcve.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtirwckufg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbaxloqq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtuqkcgstf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtnidhpyok.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegimoakb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtztbkyshb.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqikykdb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gtjirwafww.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gtcqtcsmgj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtwzqeoegt.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtnremqyuo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtuafmuwme.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gteddcljua.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gtrrotamgi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtvybipntw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyododsmb.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtosnbimyj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrlvrxqod.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtmdzqgzan.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gtcdnnofrf.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtryrvivwr.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtlmienzaz.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtuoguyiyb.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gthkoptkpb.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtzvvbeexu.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtangxosvs.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gttvdbdfak.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtvtsersld.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtzeriywyu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gtznbhssnj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkgzpuez.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtruojayzx.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtfgxjmeqt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxygxetmq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtweurzove.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gttbyfvxzv.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtxapxlcfz.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtocyzzqph.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gthdkgjeki.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtryqqcbhl.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahyqenhu.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtqzgsetnh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtjutwnfmn.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtkglisfdk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtfunbbzjd.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gthiyyxpmx.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtnqodhzjb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtloizmhfj.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtkimbpjjy.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtjaaoxarf.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gtwgtbqylk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtzrsqphbr.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtlwukqftp.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtfodgvxid.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtodypicms.html


<!-- 参考信息 -->