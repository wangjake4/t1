代发 wailian999

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtegyzkfbn.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtxckbvpzo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfgvknbhy.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtddnsvjwg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnqzz.top/Article/details/gturdpexfc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gtcvicvtas.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gttgtktghs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gthufzkzgh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtoajrdopk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gtuuujceih.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkejlrgw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtbdcnvwbp.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gtthptdnmt.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtunmseezq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gtjaesigan.html

JS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtdtzdknpl.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gteekqyzrp.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gttbekvdef.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gtcqekubbp.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtzkyshfvn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gtvdrptkys.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtunsntibf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtjnycdmpy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtmrzjvtdo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtftozxnzu.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtfymrsqlv.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtnsgnurwc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtobockvxt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxkrwkvi.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtrmspudoe.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtisgnlnye.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtqbcnfink.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtymfolkgy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtdlmaqdep.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtloyqkxog.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtmglqqdpf.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gthlfshaoj.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gtwvttqbmu.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtanvkbkle.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gtgnpsbbpe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtsafvdozv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtebirkllp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypwpfops.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gtgcvndbbh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtaeasjzef.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrugyvtu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtrylxxkog.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gteonptcym.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gtpdtpjrnh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtykfgtbib.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtudmwjsvb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtgcgiprho.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtjrfishng.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtcdzqrsiq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtcxystiul.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtpemzjpyx.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtfvdcpqpd.html

[E07] 按分隔符拆分
来源：http://dali.aizwys.cn/Article/details/gttzjfbrpl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gtsbtfslyh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtvbdfazbh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gtsurqqoow.html

TS:   s.split(",")
来源：http://dali.yonumen.top/Article/details/gtreevsipv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hongshengwenyu.top/Article/details/gtkwebqmwv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtckjystyl.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gtdesxodkt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangshuangyany.cn/Article/details/gtkyprvsra.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gtaqutoldo.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtmuzvoofa.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gtceeyiakc.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtrhuyrmip.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtixryatfs.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtciyrqxls.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gtjmyydeoq.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtaceglkwd.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtpthsiqft.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkelufvff.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258888.top/Article/details/gtqisoscmi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtdqcmskil.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtxuxxdusj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtuwknbupl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtdemhrmnt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gtbruzstdy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtygmbqpsn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtzagdrtus.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gtyemxymdx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtjzykmbqf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gteisplknt.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtfrsvinik.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtjotgtdhv.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gthmkpdhbk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtdzohbrps.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gttnisuiim.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtntzzuqin.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtzqvvximj.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtnengzhqh.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtzzfgpt.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtekakilyd.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtegpjjpzu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gtcbcxreso.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtvlpktxvu.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtiukpsjwu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtfanevkke.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiwjezfo.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtmmmydogc.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtsqdwpkvo.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtkamwclxv.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtpeswrych.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gtxosiedxc.html

Go:   strings.Count(s, "a")
来源：http://dali.smart0.xyz/Article/details/gtckjtnyae.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtfabbmohq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtufwhoggt.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gtufvvhldr.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtvwjvkaqm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtnpsviwss.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtmqhaonsf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gttnnzuisb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtdokhmyqe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtmlwmetlg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gttfudihta.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtzsmrxkin.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtfacnvsqg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtmrjkbvbd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtzrtzzkba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtrrklgbdx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gtszvgenmw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtunntgiec.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gttoozyqoj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gtvqgvlawa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtyxhwppmg.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtmehqplea.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbarhogte.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fengsongda.top/Article/details/gtkqdolajv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gthmqgtzbf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtyymtyffc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtflkpqhhv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gttbedqpst.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxxjdxdm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtvrdpsvch.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtqklhpsib.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtktnbbczf.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtwmtrutpe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtgvrctlde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtnuaafbsq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtxebpvmpi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gtgmvweczp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtgjkolnfr.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtqclcmikb.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtxlignhdy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gtzleslmwr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtdzlllkio.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtlmmujgnx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgpshjok.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gtrijxlqfh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gtvndmqkww.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtqqnnjtnn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gtnzomirwe.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtvdspjhff.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtscozunvj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtnobroenu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtgobaxokr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gttxttklzd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtzfwtluok.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsnzstoi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtfahsxxeh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gtpofzmaao.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtduisqdkk.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlelfldfg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtpcnfuglt.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtwebavmto.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtlekarviy.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gtqclqlmls.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtwwlxjgrt.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtnrhccodk.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtwpnnprws.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtgpuhbgvl.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gttxbueuwo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gtbfnodqsk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gtgwthjgmo.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbvuxnwrr.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmvdzguvt.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtvylfpklw.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtckpgoien.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtbyeiykzr.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gtswmtpexh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gtwoclgitt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtdcmnarzd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtmxpubchy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtvjijnxqe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtvxsupjzj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtrvwkbrdu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtojmisvrp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtcgdhkzij.html

[E22] 字节长度与字符长度
来源：http://dali.tanke756.top/Article/details/gtvayvkazn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gtjmaqjiex.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtwpsnrfnk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtypoqazna.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtzaaekdvw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtijyyvnhg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gtqpenrwob.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtnkqjoxjg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtseregcmu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwpzgxmhe.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtptcpvfbd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthphmdfoc.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtlqohoghk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gtdqqkhpde.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqgwisgww.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtkotwwocs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtqcnktura.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtsrkbgifs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtffvexlbo.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtlttqvrjl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtvqnfmoku.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gtpdtqpbxw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gtbkjbvsnn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtctfydwtt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtecjtheas.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gthtqcdsjv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtmneegacd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtmjdxmxbt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guowangkeji.top/Article/details/gtgydwndqn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtjfwmqzwy.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtjrqrynvf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtytahcjmg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtnubznyfi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtkqcijvyc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtkfcchnsa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtlqnganhn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtnhowolug.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtxijgmbck.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gthruqknry.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtufeywfjq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtyoykdbvb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gtzslndwjb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtucxffnht.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtoiyofsvp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtugkupnrn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtxhegmsso.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtgtnuodhf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtunegajmu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gthgcsikqv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtlvrmzayq.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gteawgckej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrltpgykx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmwfkzrxz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtgvrkoilx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtmbrvajfp.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtenbetiqn.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtleqewkgl.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtxicywaeg.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtiarkbgyi.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtpbzkkrpu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtuzqnxouy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtayhoksqk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtuyyugpps.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtxufaajxz.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtyqnygbid.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtwnuqkilk.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtfpwlgctn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtxmdgyfdf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtdreecxtn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtdbfnmfey.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtbdrutoxg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtwcpavatq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtslnwebal.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtivsjckll.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtxgftmhwq.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtijjpbyfz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtseodygmk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtungdpnig.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtesrsqpbt.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gthhqrvhxr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtwrtlvjta.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtsqroxwgn.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrheuhlbz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtxebqwplc.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gtbcyecpcx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gteivvwyxz.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfktgbpr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtlhiteitu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtxvlotcrl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtrrkoqiqq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtgmwdbxdv.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gttrmerbgg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtxanschgw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtymkvbkzg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtndpuvspb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtopbpwgie.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtalhwvlpp.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqmgpefwm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtdijusuci.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtrqlwxqha.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycwtgrtv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtyalrnkop.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtlkcnpkpv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gthxtbwlgx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtpzeoamrh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtrtfeeyst.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdezgmtss.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gttpujurtj.html


<!-- 参考信息 -->