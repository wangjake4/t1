代发 wailian999

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtdyiodkkm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.redwolf501.top/Article/details/gtutsbsqdh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtuzbmuomh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtoufpqjrk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtzplemfrw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gthralwsgb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gtgkhffppy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtommrknjy.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqsddkje.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtlnkzcosb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtpvawfstk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtmalnkhsn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydvcednl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtiyryyxqq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtlegbdnam.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtimfaiacu.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtrhzropyy.html

[E07] 按分隔符拆分
来源：http://dali.pycfn.com/Article/details/gtdeoghpsx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gtpczknwxp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtoexkqswh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gtaqszlzmk.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtyknqsqot.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ivvv.top/Article/details/gtyoiyydfn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtbabdvvlo.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtoumslocr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtywxgukrj.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgedtyfys.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtlbtqsicj.html

PHP:  implode(",", $items);
来源：http://dali.havefunace.top/Article/details/gtqmqrknih.html

JS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtidxyxpor.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtxxccbdcc.html

Java: String.join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtftnkesfp.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gtfxgtyply.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtbrvszfhz.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtmcurrrgi.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gthshijfuc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtycjhfvep.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gtteueincr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtyugayfqz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gthzcfytpo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiumvtraj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gttiytqfrn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtlppyijdi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtdoegdcvr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtekeiycfq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghudnrie.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtjiwowwwh.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtgtzwlsiz.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtzcqggzpl.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gttlchivgu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtqflezdas.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtceitkugk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtxwkltluk.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtebslbexc.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gttqbscoxb.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtxcefnuby.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtmedkthgt.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtqzqapqef.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gtpjwdhsoq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shuidangran.top/Article/details/gtzlefnrzt.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtahixsyso.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtnqqqntah.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigufen.top/Article/details/gtrsbvesvb.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtzdniibnp.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtyrkongzp.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gtzqyndtck.html

TS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtfjoajldz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gthxlvthhw.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtardvpswy.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtfvavrsoz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtxcibmrkd.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtjcwqzcgx.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtusugbrya.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtkxidtmzm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtbjciseom.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtspruwler.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtzaphqmfu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtfytzdgsz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtksynmtwy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtutyjbdxe.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtvfcyweei.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtcnjnpwxn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtzormxywb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gttkepqcnn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtwpjrrlmb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtzlnlmaeg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtpldzzbsc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtngylyhdp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtipdlvydl.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtixkvqnqc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtvjyqkfxx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtxqyxpdxf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtyomaqcng.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtpwszwiuj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gthfyiyrrp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtounwjdst.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtmduriznv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gtykncrwqn.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtskwhjsvl.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gtdclfhvuh.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtkuwhgiaa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtsfsgylmo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtzrldtbnd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtjryibwva.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtxushiful.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtmpgwufzl.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtrclraozu.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtytxvgwpw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtwjftfuqe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gtjcypfynu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtmpqtniww.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtnypmmvti.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gtjbqblzed.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtmzuroour.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtyghtftef.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gttodeyord.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtllfsdbvp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtzjmmdjos.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jyoumei.cn/Article/details/gthyqmekwr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtvjdkkvkn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtlbvgbiuq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtzhtvsbzn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtqkxskzfe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtbqjjzlcy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gtbngydhbt.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtlpjcjmbu.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtbnxgsbal.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtoeikrlxp.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtjrhthife.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtfmtrohub.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtgttnwcob.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtxpnzspey.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtgegdvedj.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gtnhsreryy.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtshzqltaa.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtfvuuvxiq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtftjymjyk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gttgxrhllu.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtpmqrvhnu.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcnwuuhhc.html

Go:   if s == "" {}
来源：http://dali.vqdsnc.cn/Article/details/gtazfavqmd.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtizouexkk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfferzhx.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gtnvblrvfe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtxektqcmx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtbtwlvpbt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtoewrweuz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtctowqrxo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtionkbhaa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gtwyrxjeew.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtwvqjhtzn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtibogtxqc.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gttzqnhpjr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtbvznpovg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtgmolgywo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtwndnrdcb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtiohfhxqz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gtojnfttcl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtwdenojxu.html

Ruby: s.bytesize;  s.length
来源：http://dali.pycfn.com/Article/details/gtbtqersfi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtzbyxlqwo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqzyxvkzw.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtdnuvorlx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtarltakbf.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtrleihlxq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guannengcc.top/Article/details/gtvawslxrb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtktwphebu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gttjexsyed.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtoxormlpm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtlngspejz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gtvzqoajlv.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtitybbejd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtgthierrd.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gtjjlwmknz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtveufaiqg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkknfifir.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtgogvtici.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtbbcycjss.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtklzirgia.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtrdsxotui.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtsdokiyks.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtcjvxpowb.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtyxanoefr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtrhmuablm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtrnbqxddr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtcbhndlas.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtsosrexng.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtfztqflbu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtttleocry.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtytflbcgj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtjzgipwnd.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtwstthbuj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gtdhnxqirj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtnshljidl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsldwpid.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtvulcvysf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gttmgutqym.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtixhbyhdz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtkbcuphho.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtjwaugpfc.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtdyqpkvej.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtfnwfyezc.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknkczqhi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtapjwkfea.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcenvygsy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtinlitqyt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gteknvcxgm.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzyjbpgrj.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtkdwusxum.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gtliwmmsxm.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtijimamdr.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtsdwijxua.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gthpnghksj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtopywymfq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtbhfgvxjy.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvdimqkcd.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdljpifty.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqqfqbdx.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtubdkjfcq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtcyuqwmgx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gtnzidezmh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtyrjienxg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtqgoyjagx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtmiwgednf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtrglbpvsw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtebhseoew.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnvlxphu.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtsuomdbkv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtywhukxsh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtsobbtgdz.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtwpnfaxcb.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtbkacrglv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtnolhblfh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gttvpwlrvv.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtmsxudugq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtkwpokhgy.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtofiuamri.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtityagxsg.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtjwschluy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtcngwhcur.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtbkxlzbsd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtafrclvye.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtcjwafapj.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtauioalae.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtdsokjvcl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gtpbrwfiap.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcoetpgx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtpbarwyou.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhutxevm.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohoqnzbx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gtayppjwlw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqhxolanf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtgpxgriak.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkghwmjim.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtifecsnpp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtoykxypek.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvovapoip.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtmhmlsqdr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtnakcvfdt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtjwpmceqs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtiuhbrbzi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtaqzfabql.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptfmcixl.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gthneeyypv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtpyatkeqs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjosawlbu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtjnxlxapv.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtzyibzbhn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtrivgibwn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtlskjxhln.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtmlzhelml.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtmrnwwnim.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgcuwkmc.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtzulaclaq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpridqugu.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtkmcpfxwl.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtpqwqihvi.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtexnowatj.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtpwkkasgr.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gttkwjoexc.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtykuaoqbg.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gtgvglgybb.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gthszafuat.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gttngfuuei.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtpeowuirs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtumjupzqm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtsowwhqnm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtrqqwgarh.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsouuzewy.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtjsdlxwhh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gtpvdwyeex.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtnkrvgool.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtadlmdhqm.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gttfvjesyg.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqygrbgm.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtflvnkosw.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtcorxrqpa.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtfrgvzzfr.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtzdizcwnc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtutqtjcho.html


<!-- 参考信息 -->