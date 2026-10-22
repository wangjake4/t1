代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2hcrhwwpd.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2qtaklwna.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2qbxazswy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2afgiiaqc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gt2aapwmemn.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gt2bjyllynw.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gt2firayjyz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daebgdok.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gt2tuzbhcwx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cashguo.top/Article/details/gt2eypbohqj.html

TS:   s.indexOf("x")
来源：http://dali.sxryk.cn/Article/details/gt2vlwsmrjm.html

Java: s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ifmyknuq.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gt2xfcraoto.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gt2xlurkycb.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2fnmjoubk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gt2cqflyecw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gt2ocffkbig.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gt2ejpbmshu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnjgtybw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gt2pgwvvtdp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2zeohxldi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gt2vhcxbzxw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gt2bbllxkjn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2ycmwijmv.html

[E06] 替换子串
来源：http://dali.316326.xyz/Article/details/gt2jmuuoerv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2bhaetoqi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqbpgkkf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2bgasmlew.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2ahitgxec.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrseuznm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2lwstggyi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2owxlafvk.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2khxsdvfj.html

[E07] 按分隔符拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2avolxxkn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqkhubku.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2trucdsua.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gt2ddueluhk.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moljjnnb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gt2fnhnkowm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gt2wkbywdep.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gt2xekcmtru.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2phcnydhh.html

[E08] 数组按分隔符合并
来源：http://dali.xinyue.icu/Article/details/gt2bvnakopg.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gt2evgbaqxi.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gt2yuxrncwu.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2obblbcbw.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gt2rsvgvuxu.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2pgxpohzc.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gt2ckpnhybk.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2hsuzcqof.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2anjqvnim.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gt2bvunndkx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gt2wfddspru.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vymgzzoo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2idmsvjwi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gt2peymgmuf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2amkwbtjo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gt2jriworsg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gt2lvvzully.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2aeqnnkmp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gt2zveksjvy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2qzriirbi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ultpomza.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2ntwnvohc.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2yxejxwlv.html

Java: String.format("%03d", 7)
来源：http://dali.birdmap.top/Article/details/gt2bfjocuwo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhitxhwy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2cpoggwaq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2wwreysyp.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gt2ahjmpjcj.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2dauddnnv.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2eulhjmti.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2uhghriww.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2tqkustuw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2etmsmeay.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gt2jpouwiqb.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2eafsuvsm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqutmcyo.html

[E12] 统计某字符出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2fcyhrcae.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gt2vhaktnbd.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiionqhv.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tijiqbno.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gt2bhyzdqih.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gt2zphbfatv.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gt2lxbpzpxk.html

Ruby: s.count("a")
来源：http://dali.cucudq.cn/Article/details/gt2vlwwlryk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gt2dgshbuhn.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gt2ktcrnvnq.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gt2ogoqcasv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gt2iqrtdvdr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2yveudxtb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2qdmuvptz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2onjdpaec.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gt2kegoxoal.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gt2mnocmxnc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2zmoxwpay.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gt2evesvvdj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2jkwmgqsw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gt2ehclosbc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dashuyun.cn/Article/details/gt2ujnrmxlb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gt2tcewenxk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2fuxxwebh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsawjowq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gt2yfxsrpkh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2zilvfgli.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gt2kmtefasq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gt2wkfjhqcf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2vmsqpkvo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gt2mqluckqe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gt2xzwhvpah.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gt2hszpaqgl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2lsezizwf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gt2cnbafxya.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gt2wlvjfyod.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2aiuwqptq.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ssgovzuv.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gt2qyweygmm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rifeiusv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2uruhwbtk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gt2mcsdckmr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2fagixrup.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hammf.cn/Article/details/gt2txopifvi.html

C#:   1234567.ToString("N0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvfytghv.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftyimcal.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gt2nrzuwqgf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwrkmumt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gt2mdmedcup.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2hwefifws.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gt2xuloqjyy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gt2wbrzqycp.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2qushajru.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gt2obotpqwj.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gt2fzngkukb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gt2fghvvjkc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gt2itbqzvuv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2kvnhlmjy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yffhmpgi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2qzaktqls.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qoubgarc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gt2qymschej.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2oejgwigz.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gt2esydwbtc.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gt2ersechay.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2giieqghx.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2lbfdjasd.html

TS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccmjnjfe.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2nwdjmgtj.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2nscmiwrr.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gt2vlqubnmg.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2pfsoukwq.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gt2ybpqreyf.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gt2sliqtlhg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytxvajsp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gt2pqbagxnk.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gt2mtufbqtd.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gt2ooyvlbdq.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gt2dhvmpmin.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gt2ahrxyyax.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2tlsqrphu.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gt2lnalzsgn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gt2qfjribmc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhntffbr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2vlmuadmy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2qyninxko.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2cfbqxxvb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gt2klbgxrri.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2kmlcdgno.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2adxwnqgm.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyapqbky.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gt2halbwatl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2jkartxbt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2ywqxqbyv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2tyrxfgng.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2vulaanxa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gt2sdyttoln.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qecpqfdj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gt2ogjnqxqe.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ezfsbrbp.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2szwdamvu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udxddmed.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gt2pgrbzceo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlrggrue.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2mgiznayd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gt2udxlwhwc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2uqzcivrv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2osusvldu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gt2vekymcwv.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2skjjgrbs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2qcapubvt.html

[F02] 逐行读取文件
来源：http://dali.shzxlz.cn/Article/details/gt2bwmkqiva.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gt2ywaimzpq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gt2wheddnfe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2faehqzkl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2izavjhsu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukwbkmap.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2khuwcsjm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2ipxqdyro.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gt2jhuymika.html

[F03] 写入文件（覆盖）
来源：http://dali.birdmap.top/Article/details/gt2dthmxvqb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gt2ajruqhzz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2wevdjwtn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2ejkrcfys.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2vbjeijog.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2rojssxzw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gt2zusackah.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gt2ottzqyye.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gt2ampvtacd.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gt2fmrdvcui.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2jvnjftto.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gt2hckpwoth.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eovekutf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2walvvzqm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2davdcxew.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2qgnsyfpt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdfswvpv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxlhywzw.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gt2ckyysfwk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2nzaongfr.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2gcymsmjs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nijsfozf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2suwncvya.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2ksiuhvuq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gt2icqlogxw.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2edmwucck.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2zafparlv.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gt2uwbaiulj.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2pzwrpkbm.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2itxtjuwu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2zzmmqgen.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2gfooasqb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2qluenjnt.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jxhardzt.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2mmbphrah.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2lnqyxbro.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gt2qmjmhbfc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gt2mfsrkhpf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gt2rogbfksz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2fmdsrmgm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2juquhjft.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gt2cldehgrm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rawxsplw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gt2qkmoyiyn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gt2sqowktap.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gt2vgqtgpss.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2dgepiawh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gt2rlyohzix.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2etsjojpr.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2jawpgxbr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2mvfduloe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2ujmgumvn.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gt2npityrmh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhhglamd.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gt2gumjxuyp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2trkytjxi.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2pqgnigls.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2yeqqqcto.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2zuibcrmj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2etcedlkf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gt2uexsflbc.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2gebnbahg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gt2hkgibqde.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gt2crrwgsep.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2djhuaahg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2jwuwrttn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2khgpgqra.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlcswial.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2ykaspghr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2vjbwsctd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2avvpjkvi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2elscbqxe.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2qitovrxx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2jeznjgzf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrcvqzht.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2blpkablk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2tbzttrrn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2bjzoehhx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2iqclnvse.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2wbwuxclm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gt2ghnwrhjz.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gt2znvkcvuo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2hdsxoogr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gt2jjdqibuk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzudrdat.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvejkevo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gt2rjufdhvb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2rpfticvz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gt2xiogktsa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avgfjhaw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2izvfwqyh.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2kuuwoljb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2oxvlxofb.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2faigrfmc.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gt2udjzeudt.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2xcukoghw.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2qwoihxmo.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2bzjrkahu.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2iewslhbb.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gt2ffwnzccp.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2smngfliz.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2kftxwxgm.html


<!-- 参考信息 -->