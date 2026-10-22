代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2zqhotxeh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gt2fdaqaiaj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fexzhoeq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwtijojt.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gt2zitpeiup.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2cjylrvgw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gt2ksxvcmso.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2llcileec.html

TS:   s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2ynjwrouo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2bneadqkt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2iqdiluhs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2ztligicf.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2sspndijz.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2riasxgvx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jiagoushi.top/Article/details/gt2pkbrpdom.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2pjhbuazf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2brejgqlc.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gt2xtqzchws.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gt2vxrvgjtg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2woufojfi.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gt2nffbwkzv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gt2joafuqqf.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crqfxhyw.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2fbkequfl.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gt2jktjcdqo.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gt2qnkqjbsy.html

TS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2dvoxktnu.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gt2cqehegat.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gt2bzrnhdwk.html

Ruby: items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2iziljgpt.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2ldyrjoao.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gt2bacjcjvw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dianchejie.cn/Article/details/gt2efpxfcaz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2bjemddwk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2pxjekcem.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eppgrspy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gt2nrifhxcz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gt2sgghvbre.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2scubwdhz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2lavzdkfm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gt2cvvhwoxc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2btbugcsj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gt2thoelzrr.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2esntfpma.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2kxxedqfo.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2pblciihh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2nsatbqrd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2lvfygmkv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gt2cijhfbae.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2dqrhtlim.html

Py:   s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2vcfgtppa.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2gecpsxqu.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2jvbgpvza.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2dznqdjog.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2inqjjdwp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2oapvoied.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2imtvdvsc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2kaizskux.html

[E12] 统计某字符出现次数
来源：http://dali.mhx1999.top/Article/details/gt2raasqjup.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxfphyfw.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmqimqyv.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2mggksdtr.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2zlautxps.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gt2zxgrkpxd.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gt2myqyjape.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2hovtkhal.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2exvqwuzx.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gt2arijnqpn.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2notrcmky.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utgrovpt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2pelxkmiy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2pxyqupwj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqcepyqb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gt2dvnpfdjm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gt2hmwdnhqh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ybcxt.top/Article/details/gt2anpcacdo.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gt2gttmmzvk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gt2jvofrsma.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gt2sgzmghdp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gt2amlepltv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2vcyrqzdh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2labodarv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gt2zfeyupkx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gt2tszjachd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2fpiguofe.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gt2fmvyqige.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvfbyext.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2pimxwxzg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gt2wexsraia.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2olhdqdpd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gt2uefbbgce.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2cwcddcfr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2aomrrhwz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2blzayhlo.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2srqpwfxa.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gt2yxufijpg.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gt2vzuflgcn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2jaymjnke.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzchaurx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gt2buazlwvv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gt2ssgjdzpb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gt2iwbvpcyg.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2gtawqolb.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gt2amureiym.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gt2kqzomkgw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gt2kilejuvd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2rqkxtuwe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gt2qiblgubr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gt2zfohegie.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2wgghxvai.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gt2kbkchijy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gt2uviecvnh.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhvuxqel.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gt2sfaqwleo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gt2zirgvhsy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2zeoxpxcj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2vzjlqhrw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvqqvizb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2wcxfoniy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gt2ntckffnp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ydzc1.top/Article/details/gt2hhkfebzy.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gt2bbjrwqsg.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gt2tchspuke.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2ouhsbqlf.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gt2nuejsppo.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2ihasdrgx.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2znujgszo.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gt2ejiellhb.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2ktmhjvba.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jflyghvl.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gt2rorncaqv.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gt2uggvqruh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gt2qytpfgkd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gt2odixuzoz.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2abetosoq.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2cpojqpnu.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2wvthklxv.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwydevem.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsumzvut.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gt2antjqjeb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gt2layuiqfb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2dfjgsdhm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxlbgdne.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2uwjaorlh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2hockehgg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gt2cuuqgmcj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2rxbttlbx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2yxawfzun.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gt2umuxppkb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqwiyeif.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srxwgpxy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2lmvabmng.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2qirgvaqk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2gbewonbb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gt2iyrjejeh.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2fducwjts.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gt2zxtoxtsq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ugrfoetq.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2nqlcicuc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2efwrziwy.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gt2lalxslxn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gt2xwxrwocc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2ysqlrhxd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gt2qaaeeugn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2vknhqsxc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2cxgeutry.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gt2lgocxuqi.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xozowupo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2amjoojeh.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gt2slnxdckh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gt2opkplemc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2eriaetok.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2dznmgouj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2hteqrxsp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2guutpugb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2syccqxkx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gt2riwwejis.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gt2rylxxelt.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adbipmxm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gt2pbzblfaw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2ohfyhequ.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2lbjhplla.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2djkbhajd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2tjuxknpu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gt2zkmjtfvo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnpmjgwo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2buywrodl.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gt2mnlmiyku.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gt2xxjkpczv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gt2oyyrxrwx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2qipdzean.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhanflxt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gt2irrlmahv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2zorxorpm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gt2gatnshod.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gt2twfjueau.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gt2pwwvznnk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2eyogteuo.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppeyfbif.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2bhscvoit.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ekolfnfo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2qzqmtgsz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gt2oarfeszh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fyfybgab.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2rbdbhuyb.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gt2egywqmkc.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2hguktxrh.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2nlnkaboi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2mgxxscsx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2swvsxiuf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2zabggjwx.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2snhovddr.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2tweznevn.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2wmrvabyp.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2gejxqslu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gt2jdexnbgu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gt2phejtqzm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2iufdlimw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2bqvnwalp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gt2whchllrs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gt2hmqqacrn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqfatfno.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gt2hsfzdmsy.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gt2qvrvwfpp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2siotuhjy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gt2ccncmazs.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2xoppeeqc.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2qunzlmng.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gt2rhwigmey.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2krwaplkr.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gt2euwasbsi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gt2sfoqqcdu.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gt2yvzuuscv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsabdvtj.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbajehie.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2vjgqvioq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2napdfhmt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2gglwxvve.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gt2qycxokgl.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ldvhbwtv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnqzz.top/Article/details/gt2yzpiquef.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gt2ncvpufzh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2thkhggyi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmzwiqvj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dugjioof.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dkzzcvda.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqrmukzo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2sfwefjbo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ndnvjpio.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zvsmaugm.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lblgddwp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2vknqzxmg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gt2nlyadjpl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2spnujhsb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2owqopdjd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2mpxcqcgv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gt2rfpdpnmo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2utwxlddn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gt2hzfwiaox.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gt2ogkucilo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2ntzfdivd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gt2zdpyoxef.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2dxbxwcpt.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gt2paypdmsd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gt2dfimrcaa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gt2rkmvglfb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2jampawdp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gt2qukerzqe.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xwercsnx.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gt2llhizhng.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2eutljfzi.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2zhgwozow.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2illfetyd.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2fmynsfjp.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2qcmoafxi.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tipcaflh.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2upmtxzjm.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gt2sadcmisb.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2msrhfnum.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2rhprsewd.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2zrngdkot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gt2iltixwpp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2viggdfyr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2lkwqkvcd.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2drofqfxu.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2tbtrqvqp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gt2zabrumfp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhocayrf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2cwdgwasc.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gt2osngxdix.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2mctffbom.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gt2rnvfshfy.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2wpqzpiug.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2yvhwrwke.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxopinua.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejzwojfe.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2jycwynpr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gt2ximeiajl.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2zxumwmmz.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2iqdqtems.html


<!-- 参考信息 -->