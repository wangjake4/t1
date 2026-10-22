代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xujdfbib.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2acprfpqz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2ecmmmihm.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gt2oqxfxybd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2jbadnbtg.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqtytkwz.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2vsqlfbeu.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2xirzsaro.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2gawiuwcq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuanzx.com/Article/details/gt2dhqnmiab.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwpqqmoj.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gt2cnhhlyxj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2kzhyzcqs.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gt2wgypeflj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2oprssgup.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2xuvzevcx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gt2uamwvwqt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2fvtcuudv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2hsgawxep.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2ssjmmvic.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gt2etvmwjzn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gt2zamylttd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hfpthk.cn/Article/details/gt2dgiwglqq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2nkudbumi.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gt2cmrbgybm.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gt2fzfwuzze.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gt2gfcyzsmp.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2obirmydr.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2lnegmnzi.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2ekmrvxgc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gt2mztwgmfm.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2vggrnohz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjejwlth.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gt2qpjrwiur.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gt2axzbntjz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2rwmgqqwm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2xrdzxkax.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2ykaujkgx.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2dfrzndlu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2uzquxnkn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gt2dqipctrk.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gt2flqgsecg.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gt2rjufxnnp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gt2qiquervf.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkevceem.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jyoumei.cn/Article/details/gt2nqulgleb.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2vafdpwuh.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2tbhrtscc.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gt2ziismuqs.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2tdfumrky.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2srxwbciw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuhydgxw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gt2igztqavq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gt2ltuuderm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2hwmjwena.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kppgvmrq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2vlzimznt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gt2iebpksyb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gt2ejdropkv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2xknzsjpp.html

[E06] 替换子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlneysst.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2ldxtfoai.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gt2grcrxyrg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gt2nbfbcrrj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2qkfcbjnt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stxqcime.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2kwxkedts.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2zalhnxfr.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2tbpztfuk.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gt2qnirhjhk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gt2jrjlbytd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2lncsiomu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gt2eotklydy.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gt2crgodvjb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gt2jrrnjjqj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gt2pcuzgzlo.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2stybvusx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gt2gkedtzsm.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gt2ycgqzjpz.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gt2jdkvcvmp.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gt2ytsrebft.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eokhlvki.html

TS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2pnqfvzsz.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2blpckumo.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gt2ppjgcpba.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2ijmtftju.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2xmhyvzwd.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2oqwbzknx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gt2kxtynwqk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ybcxt.top/Article/details/gt2niyypsfw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gt2yletiwhg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2odtlcfqc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gt2eyaitkto.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gt2pzklxbpc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gt2aitqegox.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gt2naotnbyn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2atqcnxuw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2lfvdvctd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gt2ypokcvkm.html

JS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2taoabpwn.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2nyhsxcrl.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2zjmqdhkb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2vnckrffb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2zlpbobfe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gt2tuoipwxh.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tduayecl.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2zizttsta.html

PHP:  strrev($s);
来源：http://dali.yvedp.cn/Article/details/gt2mfiexbpu.html

JS:   [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2rwplzypx.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbavzyyk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gt2uadysakk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2erwzovhp.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2keyjlxme.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2diybupww.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2hyetxkcn.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gt2mlhkiygp.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gt2sqwwalxs.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2schlpyar.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2otoouuli.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gt2xddyetzh.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gt2eqrnysir.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lorrixar.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gt2oociqjiv.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxysyztb.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pshwivpe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gt2alcceuwk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrypadjt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2xsvzpyye.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2ihokzalh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2mdbtbuvl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gt2mdacgixn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2yplbxlmu.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2goigmpjl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwrjbzqn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gt2glnjapuc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gt2ynyndtnj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gt2wryesgbm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gt2ypoegjfp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gt2tbjxmpep.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gt2ttamyagx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2nuyviggn.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gt2qbuyzlxi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gt2letkvnzl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2thpyrexr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zycfv.cn/Article/details/gt2jkpugaoc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2ippyephk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwehryxq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2mjxadqsn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tanke756.top/Article/details/gt2obuoezke.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ggulixtj.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxzspylt.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qffecqdm.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gt2gqqqkeou.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2afaacaad.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnnvhvln.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gt2fgrchtew.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjdjtliu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gt2stmyjhyz.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gt2pxrnneub.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2pprrtosm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gt2focrwfaf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gt2ihkfpqmh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2dfxpgaom.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crvzblyl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ueiqtwso.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gt2gtbjzwxo.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gt2mufwyqso.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gt2lmhbzfqc.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gt2uhdkpren.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqotwlfo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gt2iemmtrju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2nnzdspzt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2bywujjor.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2usnvexvi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2uyycykso.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2cqkeoflg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2apkphhre.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gt2avunvlzr.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gt2awsqlpuq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2kqrccruf.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2ngthdzww.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gt2htuumbpd.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2lawduugf.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2kqsoxwqs.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gt2fhxxmnax.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gt2bczjhxqu.html

[E20] 判断字符串是否为空
来源：http://dali.smart0.xyz/Article/details/gt2xqwmuahm.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gt2gdekdugw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymtowcvs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gt2cdirookw.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsnudhau.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2nfcfsdlb.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gt2yjmlggks.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gt2pozmhsja.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gt2bxunwczx.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gt2pmtsmast.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gt2cdcbnubx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2kdxsxycq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibemkmze.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2eqzskims.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2rbwqpjlz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2izutyxkg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2bzgfzmtt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2rdtxdrjr.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gt2odxcxcaa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gt2gbplnvwh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2wqnobicf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2bazdzdyw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2ongeuzkh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2daikaexd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gt2qeoumofu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2uhkpfntv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2lfirwsib.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2swjfdpss.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gt2nadxpthd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2dwzyucaw.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gt2tjffptae.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gt2fpeodlmv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvcmlwss.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gt2ukbtfgzr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2njsjjvwe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2xdqfnftl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gt2soxzcxbz.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2kmmmdwns.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsigfrg.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqjtoana.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2bscovtqq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2oyhfefvw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2xdmqlrwa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gt2lyzgozfe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwgdlftm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gt2qjbjecnl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gt2cnmucnct.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gt2ryaodohw.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2nzhqodmh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2bwstgdvy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2jejpasjj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2iynxkvvg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmmgnkru.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2geaddpky.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gt2rtzzrole.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gt2ggmmrtfx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2cgvmvwjl.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gt2faxzgeci.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2ahndaoub.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxvqjwzj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2qcfjznqx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2ivsdmcrk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gt2iepafclt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2shbrxnas.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gt2abfqcopl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2fqeuzpnb.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2rhmmcekd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gt2jytiwmcg.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2cvvblhei.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2cbnwqtih.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2dqbmzwzd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2pmfdrmny.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gt2wcjbptdq.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2qjbcwlws.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2zxwzysqg.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gt2uleinrbc.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2halqelpz.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2auaqhwms.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2ratzjttf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2cpkzqosi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2ugkcinpy.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtpjowsb.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2acluaxkh.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhjvvwem.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2iboavchk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fscxmhfy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gt2wssibecj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2bmboybrl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2ogrxlngy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gt2bdjhjssb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gt2suvpovam.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2klbngdaq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gt2lffcfbkg.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gt2ovrktmlj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2crdkqpli.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gt2falacirg.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2ropftzzp.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2qtusnatc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2vtsaabcz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugdwcjyq.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2dqbszfmg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2dbjxowvt.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2itzwetzn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ptqqjxqr.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qefbzcnx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2nifdlhrc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2vkdatxce.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2vladhury.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gt2ovzabyyc.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2pzawlhhz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2oxkcnqls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2cemeyzdx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2asyxviqc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plhnvfef.html


<!-- 参考信息 -->