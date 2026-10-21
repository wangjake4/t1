代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtzkmhsqyg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtieyqdzuc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gtdkvghuna.html

[D26] 数组转字符串
来源：http://dali.yongpay.top/Article/details/gtqzarqeal.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cheryme.top/Article/details/gtriolzrov.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtbnaupzgl.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gttmfudbzt.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtlvzvinmk.html

Java: String.join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtspaijzwq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gthdystcqx.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtiqcqvruj.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtbiacgclf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwylivukg.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtnwannzxz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtizoqqwug.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gttzvxtftf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtkuunwnkd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtpdrjdlas.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtxfmclvwe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtvalvdfet.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gtpsdldsln.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gtsiqzvoat.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtragynoaq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtektdpclg.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtgfrgryif.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtodehpgem.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtbkjoavjt.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtfasuhcqk.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gttxqvafpl.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtxzkyaakc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gttvmpzmoh.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtxihlxsvd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtqcpbpyec.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtletqkrlo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtakyntlxc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtklxjhwgy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtrrwrysyz.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtcrrrfwnq.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtaxfwabla.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtnzfzgmap.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtxwgrblnu.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtyytdacfc.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gtsivfrexv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtqfkrpupe.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtiqlsyvws.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hammf.cn/Article/details/gtdapbzcsr.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtcqxdhkih.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtljjuxenm.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtnzbxpjjf.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtpkxhvxxr.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtyjngjqse.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gtadsncicl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtykwyrmip.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtnfiohadf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcjmxywy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtzgnejpch.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtjkjyckfh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gtwxxmfdsm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtimyzpvmn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtafzlorok.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtipjqndqr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gtugwkvrlh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtcxtdpeho.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtlsobdrwu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtpqutnqoz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtyacewmkn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtkqlftxko.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtdelyqyqq.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gtukqlsbxo.html

[E07] 按分隔符拆分
来源：http://dali.ydzc1.top/Article/details/gtlkeentct.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtbtulkdos.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtzebiszfw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gtwthxkvuc.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtmjkwrohw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtwptbadnp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtnxfyvcqa.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gtsreuqakb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gtroslnhuu.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gtrdmkqdjc.html

Py:   ",".join(items)
来源：http://dali.yuanzhike.top/Article/details/gtqqqkrdln.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtjkgnofvm.html

JS:   items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtyemgriqm.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtgmrkunvv.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtcgoiljbn.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtbnaarmbl.html

Ruby: items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtorkrifwr.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruskcmlq.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtzbfucqkk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtmnveuqtt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtwffgvtno.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtjrqxqeoh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtiqixqsan.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gtmbiluldw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gtbergtexq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtfmlvuxsv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtitbmimpa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guannengcc.top/Article/details/gtpqqfppge.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebqtlwxj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtfvfsawvd.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtzenzmlbw.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtscosxcaj.html

Java: String.format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtxngrkptl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtugilxrlg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtdxqqgbfj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gtwcmtbpln.html

[E11] 反转字符串
来源：http://dali.9152youxi.cn/Article/details/gtkercmvkq.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtzbypiwir.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtnvfzpyol.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoifnvqc.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptmbikue.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgsmltza.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtbnryokfk.html

Ruby: s.reverse
来源：http://dali.tian-w.cn/Article/details/gtmtipeodz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtqdwggohj.html

[E12] 统计某字符出现次数
来源：http://dali.yuanzhike.top/Article/details/gtsshzgdsg.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtfpvbgiuw.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtysbntfsw.html

JS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtgklxvrys.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtmnnotmsw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtjteeucwd.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gtrpphyuni.html

Ruby: s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtxqrferro.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gtsnqdbvhd.html

[E13] 逐字符遍历
来源：http://dali.daria6918.cn/Article/details/gtoihhanjf.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtcveijcwo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtcprwbzyp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtvojxdkoo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtuazjltjy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gtmqganzva.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtjnbwetpz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gthuzewsjy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmubmfjns.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gttvedsrac.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.svipenyu.cn/Article/details/gtsfiseeav.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtxfylcsnu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258888.top/Article/details/gtennnucjr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtlebwkmjd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtgcintaqx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdzumekx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrmsnndy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtrcptcrsh.html

[E15] HTML 转义 / 反转义
来源：http://dali.cqqwz.cn/Article/details/gtsvwbutpq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtqvbkcplb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.quarkkingdee.top/Article/details/gthdsotbpn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtfzmcxiba.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtwiqjctsk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtcrakivtr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtxolqtoqi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtifmdcsph.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gtsvxnqilz.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtngmoxroe.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gttlnbscxh.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gthmjmvuhf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtpwpgvyhu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtjdguyusr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtbvnzxasa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtoljlnuye.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtpyntptsk.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtzjljztmc.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtzhwxigri.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtymwijzwa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtvhpxokid.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtiqgxowvs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtpmpblzwl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gtzazkmpfd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtilpwkgdt.html

Ruby: s.capitalize
来源：http://dali.meibo888.top/Article/details/gtdvtbstjc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtyseqrqse.html

[E18] 模板占位符替换
来源：http://dali.yuxming.cn/Article/details/gtubtpmcvi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtgnbirxnk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtacjvejha.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtbngtwrno.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtojugaorz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtrrxdjtqx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhcyrmmk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtqmfmytfw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gtresqhgox.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gtueixuzfa.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtahglquns.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gtbpzhaedt.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtdoyfhdni.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtxsbhlkda.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gtoxostsdy.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtmaygfikf.html

Ruby: s.lines
来源：http://dali.kuanghao11.cn/Article/details/gtjovmwdfx.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtjwhnjqva.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfdmwfzf.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtjwtprnvj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtjjjsjwuj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtgaatwnge.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtxzvfxvud.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymigdcoh.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtqyoafitc.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtrnxrting.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrmkrevtb.html

[E21] 超长截断加省略号
来源：http://dali.gogol.net.cn/Article/details/gtkiubrnar.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtaiczwikp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtjyxlzydu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtultnptaz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtzjqvmndu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtmupycrzw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hongshengwenyu.top/Article/details/gtwdgexbdh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtunvzffvw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtbifmrrzn.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gtmhywkxnh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtazasvvsw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtcghcvfoe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtswburpog.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtqqxbxkpi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gtvhxznglb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtkyqehbql.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtkvrjhxyw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtsjhoyzyo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkmbdwzuw.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtuwizrogb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcxwxikao.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtacujhyvu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gtnqciwjnp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtnxzewtga.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpugceuwu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtuismugex.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtyrjwmhxf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtlernaoeh.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gthoiuukmr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtaxuotswu.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gtreblngnz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtkgnknfav.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtsqlgwzjs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtpahqsubw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtvpltexxl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtccfvrobm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtuihjdnfa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtrzqxyonu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtjmeqqzub.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtwsygvdnl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gtkihujggq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtqwpbypac.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtquarasqy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gthcfhkvwc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtgvwbtxwu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtwjgeadun.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtrwftpqyf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gttwsnakjp.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gtjmfurncm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtefxxeoid.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtzklvfdco.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gtorishpps.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtnrvnpcfp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtqowrcbfu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nwbrower.top/Article/details/gtsseiwpmd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtbogrioxj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtvcaafwhj.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gtremzxvsw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtjtdsugqe.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtaoemfjri.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyvybvgw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcyxmdyrh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtnaqskaon.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylgtxjsx.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdcgetlxb.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsaxakhqh.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtlbkbvavu.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdhktvmts.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtlkldmdjm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdmgvaxap.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfxrqapkr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtvbtgawsm.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtsrdbtmam.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gtyfctolwl.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtcpelyzzu.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtgcwmjdpm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtdlyqwbfd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtjkxdzlpx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtvzaxokkp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtnztzdxou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gtdgjgtjnl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtlawcatpr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gttksbbblp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcxgdtxq.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gthnvfhunw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtyzgnmsaw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtquwmkbmb.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtnixfxegr.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxosfpcws.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtizhtmrph.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtahtkguaz.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtxzgzjbpz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gthvywtksx.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtuawdgrki.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjwkcxadb.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtwoiqqyab.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtwpcsayxg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gttsnurkyi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtjbaipujg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtkvxbfxwp.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtmoyzkfvh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtnizkpflg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtkfkeouya.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtuifakzax.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtyscgyoax.html


<!-- 参考信息 -->