代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtjkjjiewg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gtfezgudpd.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtnxjafiso.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtybjwkxbk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtjstpydfu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtucrreflz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gtwsweuxjj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtmffbhglt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gtvbltwgia.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtcxyfrale.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtssbbhnle.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnoslynw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gteqsskujm.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gtzexxlpxt.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahegqrna.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtxtzyzyzv.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnmdichq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvtspfyl.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtxpeonceg.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtuzmmcphf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttvxqrwjj.html

E. 字符串处理
来源：http://dali.birdmap.top/Article/details/gtlkjkijim.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtybsrrkum.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtbiksehcf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gttedsxoaq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtmdxclifw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtzrqhfdla.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtshbztdev.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtzqsphrec.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtzqlocwux.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gteczimgaz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtadfbqkwk.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gtvdmbvpuq.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtiueknanb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtjautpwss.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtnuuwuyuu.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtqdmrgcml.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtzmzcevmy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gtmtztkuoj.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtmhgmdrhe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtngrdmxyy.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gthqxpjvwc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtdevaueat.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtkxkrdjnc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gttihcljrq.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtjujievtu.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtkfnmrynz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtbysirrrf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtzwlxqwcv.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvioqpij.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gtnlezktkn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtbwjhqesg.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gthqluuykp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtmcihdyji.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtdyscdldt.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtedvsgwlb.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtzgevcdyb.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtwmqhzkeh.html

C#:   s.IndexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtkngmtcvq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gthgbsthxs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gthahfhaam.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtsonqwuga.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtlwpwwupy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gtrwknatxr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gttkdqhmld.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtkklmdibh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gthgtzxbsc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtqbgaaahl.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtdsxbecad.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtodeyutcm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aizwys.cn/Article/details/gtuchvscib.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gthancwwgj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclhsepaz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtcfcjrtgz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gtwbkaibts.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtwggsbisl.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxcmudbo.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gtowxaaprm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gthzwxrcld.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtdcrlfdqv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gtandfissk.html

TS:   s.split(",")
来源：http://dali.gogol.net.cn/Article/details/gtzompugnp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxuanxn.top/Article/details/gtwxxvmagq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigufen.top/Article/details/gtxzpjoxyf.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtmvmmrccm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtbnzzynyw.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gtexuajyoa.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gtoikfskzp.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtwqconllm.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtkrlclyqn.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gttmfjbtbi.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtsrodcoot.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gttvyjtcqw.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtseacwxvo.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtagtvuvuw.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtiteaxvlf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtmjpktsrm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aizwys.cn/Article/details/gtrhxbjnvm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtnkwkrbwe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtqhoypiyp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtdihftyfr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtreotxiwj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtgkuotign.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtedijplsw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.mhx1999.top/Article/details/gtbammukyz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtzjlohdry.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtbtrsnctp.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtmfrufutw.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtosbxamkv.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gteurjukly.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtewzewxpz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtxqwvegxd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtywxjkxuu.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtugmszavt.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtkjmicrfk.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtdtcivrxi.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtcfkppyzi.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtjyonzktu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtdfmchhxa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtimjqmgia.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztahzhdk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtfixaxqrh.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gthtbhivwj.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtdqqsitmv.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtgfgozexq.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtglnvxxvi.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtqzjhzbov.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtnfvqldiq.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gtixltdfhy.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtcovrgfrz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jyoumei.cn/Article/details/gtbedxcoiv.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtjduuwmwp.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhjdfjtk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gteimwrfwt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtrvnchlqm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtcxkxinra.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtnlgdcsmo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtbrvezvab.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtmkqcqjff.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtlhjfcjzf.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gtbgxcdncf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gtrglqexxr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tian-w.cn/Article/details/gtlohvytdz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtbrjkebqw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtdnprncvq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtxmpsplkl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dianchejie.cn/Article/details/gtwwklvcqx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtegabvusa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gthgngaili.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtkqfawzgp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gtpxnytfec.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gthpebnoyi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gttaimqjcz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtbrrnagza.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gtonfngwnf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gthtuntodu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtkdnkotgm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtnwhnzizl.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gtpiiphnbp.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gttchvyjdp.html

PHP:  number_format(1234567);
来源：http://dali.ivvv.top/Article/details/gtycltykvc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtnfegdtsi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtnweqhypg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtacltnljf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.bjfxy.top/Article/details/gtruzpouzu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtrtfwnwtf.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpccyjba.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtpudbuqvm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gthzflxxrq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjgstgvb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gtrngkaqlq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtxiwebtvb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuexbbgae.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtjvezmemm.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtdmjwqkbr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtvotywatp.html

[E18] 模板占位符替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufxtggdc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtqmjdjdlo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtiabkbvju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtbeeortmh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtbdbbfhpr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtdevbvgne.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtgfjploep.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gtbgmgiihi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtddfnrlpy.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gtkguxkwfb.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gtxhkerqud.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gtwwsxrplc.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtuouujezr.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtunuisfpt.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtctpyspfz.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtrmjwtzil.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gtijeegjob.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gtwtnybjzi.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtaxytqjtb.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gthwvscwyk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gtkycgzmgb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtzhshlbfh.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gtptqlxscr.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtxavkvwft.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtdeuvhnqs.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtwdnpzrzb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrlwkheco.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gtlpvpvusl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtjbwcydkg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtugomkvrh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtdyufvxrx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gthbexmczh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtrywymbgs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtddyxniwd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtlzipeuaf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtvdzozpyf.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gtqndqdrst.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtmciweuge.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtcvoctwtp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtzofbkymg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gttvdujprn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gttqfgryim.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtkqdoxccd.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtkxnwrgqn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtqxbhupaq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbclbfqji.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gtxjkucemk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmimvjaia.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtfejbjape.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrjypgas.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtofsbdpjo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtfbjltcnj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtgnrjpsmx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtxpwlmtul.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtjeqaczpl.html

Ruby: File.read("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfacylxtk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gthwkaxuli.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtuvbbtqlh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gtgeghntbl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtxcirqwjt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwcvrylce.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtoyzavqrd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtxnhgrzow.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gtptlqmbxp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtgllhvimd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtefzvscai.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesjhnaci.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtukoadvfr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtrhmuhxco.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtzzdyuzpq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtjduxcjvg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtubjnjzsn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtjxezgtqa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtsvjsbgnx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtgkfudtud.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gtddgwbqmx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtoooptnbv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtbvsklpev.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtindljmyc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtdzrarsih.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtmrpilmsb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtmbnfnbbi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtqfytephk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtodryyzgy.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtnsycccww.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtgvszxukp.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtdjagtetp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqkbvenni.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvlaywjxc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbvqgietx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnccrulf.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttimwrhkf.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbjyuwibg.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtbopvcbzc.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtxhifwcxm.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtyfnhvlyn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtdiopkyzh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gttffpmvxo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtgpckmywm.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthemsxbrn.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtmziorkjz.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtinevvoej.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtfqsnarjn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtgbtyhpgp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtaedmehzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtzugulqif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtowtfqiak.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtdszymgmo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gtibbmiljp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtmngbczat.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtndrniuvv.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gtyqcfueah.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtdxzudqun.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosnyutro.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtuprtvcwl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gthsishocz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmbbadya.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gtjdxpsszn.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtbplqmtvq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtavgwrjnv.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gtjfjdvbeo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtisvrhwtn.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtvmxqfpub.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtyabrlsex.html


<!-- 参考信息 -->