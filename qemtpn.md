代发 wailian999

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtvzxdkchb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gttsqcqewy.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtjkpblcrd.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtixnfzwqf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthovpwzmn.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gtmugealzp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlkglihnu.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtribpjzsd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gthhtyqbvs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtuvznjxpe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtqscgqdyw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtrelwmpqn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtqzerttzz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtoknqobzw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.birdmap.top/Article/details/gtnfcsbasv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtnxjxtodw.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gtizkvpmrg.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtnquzpypj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.iojbl.cn/Article/details/gtspasqggt.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtsidpeehs.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtfdgtkhup.html

Java: "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtlurmmgyo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtplheabmr.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtcitengnt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gttvsozdla.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhcnaywh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtyscgmhzy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtajzclroj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtqpwbgmfe.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtmlgoqbcr.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtibsdqzby.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gtbohhomtz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gtttmvzizg.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtayognsvx.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gthqzgvgns.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtuovihbjx.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258888.top/Article/details/gtuujgjeyi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gtohlvxneu.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtcpwulodz.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtwhuxnifk.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtoknqpteu.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtnqthehaq.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtwvyfrnqw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gtfdgjtfzq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtpivyypym.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtywygffbe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtbrjlrfnc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gthzxrsnrk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtzcqfegne.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hongshengwenyu.top/Article/details/gtmoqepfbw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtitmmwobf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtrfznymuv.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gtzvluvrff.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtepbwfbkp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gtlaahmbbu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtgpsjkpak.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqnkrxzp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtgoudzarm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtfuiyhuxo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtuhxzmvae.html

C#:   s.Replace("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtfchscnla.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtjknrvnsv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ivvv.top/Article/details/gtomsdvjdl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtxlhchfng.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtsttikocw.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gtdeobqzdg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gtcqopkhve.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtqfvhkuzx.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gtgjogpoeb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gtnpicamqv.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gtryuwtzuf.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtdyvkygmt.html

PHP:  implode(",", $items);
来源：http://dali.hfpthk.cn/Article/details/gthlrbdsqv.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtrbmtppcr.html

TS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtcxsdrxuh.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtafaoxily.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtccbjvasu.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtvvszickc.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtmcmtvdxo.html

[E09] 去除所有空白字符
来源：http://dali.iojbl.cn/Article/details/gtjqmmhdte.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtvtzbllfk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtwembwfuy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtefygivse.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtvrwpssvi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtfrdogkfj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yueranfly.top/Article/details/gtqzvmxfam.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtujwmhiew.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtlqtxuawd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gttvzeeloj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtrrlikzwj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtgwtyiosk.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gttnxikthr.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtosrgefut.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtgvosnlgo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtyxzgbobc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtjwwritli.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzznndit.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gthluhwhkf.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtwjnimgcy.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjcijqvr.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtinutvznz.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtulcxhwkc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiwlfdza.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtgqnuytsq.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtcdmpscyl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtesdcxawa.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtmmtznrta.html

Py:   s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsooebfyj.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gtajknjtpz.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtpggqxmso.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtmyrtkwnf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gtgeswfowo.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gtqmmlzqzt.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtqqkgqxbe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtbsfrpjgq.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gthwifjigo.html

Py:   for ch in s: print(ch)
来源：http://dali.9152youxi.cn/Article/details/gthzdwnclk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtnsmrfnia.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtopjucasx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gthceljhll.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtiwtrtuco.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtxgrxzxbs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtoxbxxoqh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtkamftimb.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gtncoutwwa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtdjdpsuqi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtuusdqeqz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtvefmxjjz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sufxvd.cn/Article/details/gtfnmikxcl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtuhsrmicx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtsjvrywip.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gthhhxhnic.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gthmzpzkew.html

[E15] HTML 转义 / 反转义
来源：http://dali.haohaochexian.top/Article/details/gtybrkofpu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtauxeuuas.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtnnfjmnju.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtsgmrhsfi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtlvdwcqhm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxinkj.top/Article/details/gtzxxztsnf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjydcwbdw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtsdjmzpmj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtfgjygcoz.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gtkxwtqwsb.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gtizpyqbev.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtuvllvyqy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gthbqxvkad.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gteubmgwqn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtcxwgqwmq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gtqgpclmwb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtxoqekoyb.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gtikdxvtzm.html

[E17] 首字母大写
来源：http://dali.iojbl.cn/Article/details/gtbzjsijwy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtimpfuzsg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmubuchdu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtejdskaxr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtsiiahguu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitjqofot.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtzsafhdoj.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtcpwsphnx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtufhoefht.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtfulsyjnc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtvvajjaah.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtaygxuzmm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtcpnasszc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtoogxrsqo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtpqguxmit.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gthioismmv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtfvhpkzto.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtjfmaasqz.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtzybkkjud.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtcwzpardc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtrrjzkemx.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtddcphgii.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtkvrisptg.html

Java: s.lines().toList()
来源：http://dali.guowangkeji.top/Article/details/gtennhgvrd.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtfgwnseio.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtdplzfcie.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtbqxcvzbc.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtkprrwbnq.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmednwvcp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtbfkrcsix.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtfjzipokl.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtqbrndyxa.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtrlsfbrsp.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gteydndywf.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gtkzwzevmj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtvirwosfv.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtknaqgkey.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gteqtgtkuy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtxtanotvy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtnnltvvuv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtjmqkdwvf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtqxojpmyn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtioucmirr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtqunmakkp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtktrtbxur.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtampabmwy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtdnshtpbs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtxlmrxjrz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtgdjfhdcj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtycmgbmdq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtvsqxrusn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtoehkilyv.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtikhqtfyy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtuymrotcl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgxblkmzz.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtyvdcqylu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtozeomelx.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzggemrd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtftjifhye.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtnnagcmpp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtfqsorgnc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhawosdv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtcuivpqlx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtyuvijnzl.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklqeytiq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtaqeqbalc.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gtonhsusqe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gtbwvrkgka.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtrtufdxlg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycgwmsky.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnaqyizmc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtlalyjira.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtnylwepqh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtwpbfwolo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gteuqwnyeo.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gttnwhfbty.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxuotrlc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gteneqbphq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtalokkhjc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwscjyphs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtufrbistw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzqhqwlr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtczbixaug.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gthxeoanhk.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gtpftyofrx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtzxisjfrn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtnbwdywul.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gttizrdafx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtdktktvvj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmwmgeec.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtzjpibmwe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtybmtuqsf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gttooqblfr.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtrxfvaimo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtoqiublsa.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtplrgwbhn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjhffequg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttmxrcmyh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtjiouxsbh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtivxettie.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfdfvyjzb.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtlciiboty.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gtujwjtufh.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gthytyudlh.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteznpclnv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtkzhyhdml.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtdtjvxjex.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtdzylncio.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvabnnwck.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtklvxaqwa.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtpfvbrgmg.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gtyjgchqsj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtckzxgyol.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtwpnqrycl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtlxxfpbif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtbaxcwxfm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtxeucyqzr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gtckzwuwzi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtfzfgupjv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtnoqtyztn.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gttqxscaov.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtcwzksyol.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gthkvyfkbk.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtsihkugvs.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtzmvnhtyp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtvfwwmint.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtqwpthzcp.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtcekhrgkk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gtmhorpbxf.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gtjobwiqkc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmpyxybba.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdeukybhe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtvxrtmlld.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtbjmdzewc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gthuuxfhin.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtgriwjzei.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtrtmaefcx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtwdzqnfbm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtzqrxvuxi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtggrruigk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtddmwovhm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkcbvrfdq.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtsuvuftar.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtwqhnmahg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlrxznhoq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrmndszfp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtidsidgza.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtfuzlhmoq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtfwdoyiss.html


<!-- 参考信息 -->