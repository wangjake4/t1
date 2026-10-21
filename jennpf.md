代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gttqpklitv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gtfvemhnmm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gtqhfptkpt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtofdryvjj.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtipwrlrkq.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtxogrhisd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtupaltujj.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtirlxaqpu.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtipccczwm.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtsvkshcfz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtqcnsoaju.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtwrdpczju.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gtjvfiynzo.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtzyynrsns.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtzbnrpuqr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtpptkwptu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkiupghd.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtklegmqyp.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtjouuddur.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtuphoasas.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtasthaknf.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gtsufoznee.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtoyjsdztr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtlvscdmjn.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gtlishuhxb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gtsrsrclkf.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtezbevpsi.html

Java: s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtumxtaqmv.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gtjejxnytl.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gtaehfmolf.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzapucuj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gtqbmgifna.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.c1oappe.top/Article/details/gtentuxupv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gtuouatgxg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtfknxlsjd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.bjfxy.top/Article/details/gthhzrnnfy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtjwmjukzk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtklaqifpg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtvrtqvdop.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtcrqqdlxq.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gtzmmefeqg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqhrpqzss.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gthwnnflul.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtsrdwggwj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtaalctbxb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtsssswscp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrveoeux.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtomgygbjd.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtzafewcsa.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtklglwcnj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gtvjdntlgo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gthjvodfhm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthdixcmjq.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtmxvjenfn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtxqhqdzut.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.iojbl.cn/Article/details/gttjqysgtv.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtajzakkhk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtsgafrzjz.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gtatdmcxfk.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtrgyyvlom.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gteyswlxvv.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtnagftzep.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtvcssgjby.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gtulqxdzks.html

Go:   strings.Join(items, ",")
来源：http://dali.wangdashe.top/Article/details/gtzgmshxac.html

Ruby: items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtrwnuzkqj.html

C#:   string.Join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtnauvajgp.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtrnbnooxr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtztbadekz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gtpehexfdr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gtmhpupfbg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtmnnmztzu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtxfghcxzj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiacxsdkf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtfsgaqabo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtgqessxnj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtxqlyybtm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtiqstcgiz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtkygrorav.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqxpuqlk.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtbowduixg.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtrkhcyvvo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gteexsmccl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtmkxjpesz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gtmchelorl.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gthkvbegpj.html

Py:   s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturjyikhz.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtqircjtre.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtgfdqritj.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtlylkgpyy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gtjqimuzbk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtildpeqkp.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtcpzkzctl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtbbhhyirr.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gtrhuwpsrt.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtxxfzfzui.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtcckqrnnw.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtgmigvgiq.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtpkhjchsa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtvkkpujwz.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtgfhmxbvg.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtvehnhthc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gthqbtssfu.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtlbwglewe.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gtgwuioryb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gticbmoelj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtclotffis.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtkfpbauci.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtjiamwqok.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtyogioksl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtwpyegxgu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtyckeivmi.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtrsghsnnz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gtgfdidbqn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnqzz.top/Article/details/gtafdnpzzy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtxgldtvqz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gtofvblbrc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtmxedauaz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gtplhynxxi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtnneqbygd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gtzklnwlnk.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtqhwxxesu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gtkmaalazl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtxhravarv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gthqfxsbdc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gtsprwvdwn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtinznjnwx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gttswpdexf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtzvmnqknm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gthfssvhqt.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtvcnbdrly.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtdrnvvufs.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gtdsoqtwqs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtxnxbnmxl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtwlwzvpbs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtcscqlgyi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtoitzrhja.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtbqmfchop.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gtdtpykyzn.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gtqhcnhzxx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtgaeenhxi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gternlxmwr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtptkgdtcu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gttmwvqcmm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtaidupfsq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtmpewqymb.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtvyftejqc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gttrjsqycg.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghfhngnr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daria6918.cn/Article/details/gtrbolkajy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtjztqmlew.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtzpkoasmy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtsahwfuwo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtlhpnvyor.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtmczeqcci.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtxpmivlbq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtxzqhcvwx.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtpplvndbs.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gtwfsmbfhz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtoasvzotq.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtsbeanhml.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtehpldrsh.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gthpbovhwt.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtpahgtiri.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtchqwsywt.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtnqmletdn.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtjysccjkz.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtgjbcchee.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtlcyfmjwi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtcmtfwsor.html

TS:   if (s === "") {}
来源：http://dali.cucudq.cn/Article/details/gtfgfdeqnf.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gttotwehjc.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnthwjldc.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gteudyavpz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtlftqpxdp.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtjovdzrdz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gtbnnvifnc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtwuiixwnt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtscqzrrof.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gthpnmcrgg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtycamiohz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gtaflsmbyk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtruvjpvht.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtvfuvrfla.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtkfwnxxgj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sufxvd.cn/Article/details/gtxzlpxlwd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtgjsgpsae.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtjnmwwski.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtcwbjclbl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtcdmvywdn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gttfvmdhfw.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtpunuolps.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaqimsee.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuopapzlx.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtrfrzonak.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtoqaxekcv.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtohjcwesk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtcbibjwfm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtnzfpsgwr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtafyjricj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtaehrdfij.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtedqflgqz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtcqxabvwd.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtajjxfijv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtqbsisgns.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtjsprxujd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtjspkvqhj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtbebmlbku.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtrkpuoxfq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtieynbluu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtgdzinntn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gtsrmaline.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gtgerczlxl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtyoucbkhn.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtarqqujqm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtdbkwaqxv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtrcdxkduj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gttvyekjlm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiqueaku.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtdiduhaty.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtzrjwhbbn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtltlcafii.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtrflqrbhw.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtufarswqa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtokmsevcv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtncmemist.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfjhdage.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtjohmkvww.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gttqydtvbw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gthmhbdrpc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtyylclehy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtfbpmxoqs.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtdzguqcaq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtsfyhecuf.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtqqveeuwu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtaapinamg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtjnjylfqt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtwgtwxawf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtvigkyhgj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcmqsmjja.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtnbjfbabw.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtcejpxjdo.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gttlaadlmw.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtdjkegsdn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtsnhosenf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtlypqwsou.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtmrzscjqt.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoresgstr.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gteooribzq.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gthcybekdz.html

[F07] 创建目录（含多级）
来源：http://dali.zhiwuduotai.top/Article/details/gtzuquapsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtoqkfgnnm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtegfudgxr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtolaixvyk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtbsbliwoe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtejfwcvpp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtrjloybin.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gtubmiabel.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtynkrxrno.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gtoekhkqbr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gtvwhybzen.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtnbetppvy.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgpyjfxy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpihjzjx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtesbazkkj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtfnvnstvf.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtialyihwp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtrdsfjstv.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gtqyfiipba.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdeesqhvn.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtzfgcsiuz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtfyqhuviq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtaopvcyml.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtlqhhbajv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtwuhlbljk.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gthmrivrqe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbvimgge.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gthyebhyrr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtitrhuigw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gttfrhmyax.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtcmudbley.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtopwimbal.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtbjuxvknu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgtaledkz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtrprlphmb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtqnkpqylw.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtmsizrckd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtohdtgglg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtegfwftbu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfapkpff.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtamxfuqja.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtlzkttrev.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gttgxbdrqf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtzpxdckes.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtnxutgqwj.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtejfcmdwj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtnynxllnv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtccimzbbl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtoheuipmi.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtlgtssxlb.html


<!-- 参考信息 -->