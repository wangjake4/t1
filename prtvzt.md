代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gt2ddddajlb.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gt2vqkrsdlj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gt2avkqkbrz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gt2lcaggvvd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2knvhkule.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2sibnmptj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2qafyumxk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gt2dqyhdcoz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gt2wxybwdeg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhixingplan.top/Article/details/gt2glmmspyd.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gt2shtohmbm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sufxvd.cn/Article/details/gt2mmurluui.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gt2myoyjoww.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ehqftask.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yldlnccg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2vqcimyjr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2fcztkeyo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2nwfodtxn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gt2pvpgtkrz.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2rdiinimi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gt2wfvhrbie.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2iynfpush.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2tezpmuoc.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2spyvytts.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2ujlaobcc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztdhmzur.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2amivxacx.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gt2euprtryp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dsmmklzn.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gt2joyalfkm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2bonhmaeb.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gt2ayxwiosz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gt2mhybscwe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eaearihw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gt2surkcaia.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2eigftvez.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gt2heojqakh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2yddzximd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gt2lsluzbxs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bavtseyr.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gt2ehlbydki.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gt2mqmvrvqe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gt2dggpcmwp.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2fsouhqxo.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2nqeeuhss.html

Java: "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2hmskinzi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gt2ktiaokwg.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2hfvckgqh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yonumen.top/Article/details/gt2cogbomff.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2bowlphdd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gt2mxmrodav.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2fchxhahi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2mfmjoppr.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2assgylom.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2qvathwht.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gt2wjoyhquz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gt2oucyjduz.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gt2eoagmfzj.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gt2esgqyizc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2aqxugvgf.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gt2hwbwfoji.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gt2tqelhqfn.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2osksdsva.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2fvjzenax.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gt2deafahnr.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gt2sijvygtr.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gt2ltttweoq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofejqfxk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2srwtnlob.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gt2uecyhigq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2kchjlpox.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2jwjwlvrd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2ipaovket.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwwjgubu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkccrzn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gt2ytwnpvzv.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imxeiaex.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjhprlvp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ivvv.top/Article/details/gt2tbsdptng.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyyxsbqg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2iiwuyvpw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2ypiwfklc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2hnwrjndw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2gmpxenvh.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2idfdvwwk.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2tzpeoqrh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gt2dncuxhvt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2eforxogj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gt2hgfkikyp.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gt2ijtbafhj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2trifvrkz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2kruhjyqf.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gt2flxudpex.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gt2geebodnv.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gt2mrkyohnz.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyqfdyfk.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gt2obgloogw.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2duquicvn.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2bvzznurw.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2xoqbhgfb.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gt2aszfpvcf.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2rvvqbasw.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2uevzxase.html

[E09] 去除所有空白字符
来源：http://dali.yueranfly.top/Article/details/gt2nephwgyd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gt2ngvlxset.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2knwuytyn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uenovnmx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gt2niqmbtrg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gt2pbxtbzml.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gt2kiaruzvl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2expvsgbk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2ndbbiffb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gt2pquiqvfq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2qumgknbg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gt2dadftmyd.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2gsxqidar.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2qmhxwkxg.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2ittldygp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2jhueexaz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2xyeoxneq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bchoenjv.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2vtysehgd.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2usaylxxx.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2syxsibpg.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zoovmyyc.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2gafqnunk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2csodngcf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhqfkckw.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2iovaqmgw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afuwdisp.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gt2fgvhselc.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gt2ktfxhslk.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gt2chscmqas.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gt2eftaevvi.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2hdxrvxef.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhengqikj.top/Article/details/gt2bgtmymap.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gt2tjckpwho.html

Ruby: s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2jaexxjsi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gt2qzwidwrg.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2csbxkxzd.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gt2sfuhepxc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2axyqvthk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gt2jhitijis.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mzsfdzuw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2qgshaojn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gt2fdfmrkkd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gt2wgnjoqld.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2csutvwwh.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gt2rmjjffqr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2qejzcqek.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2nfvdeufx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gt2grtbzcur.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gt2egzeewie.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2klldcftu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gt2rubcsrne.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gt2uiaodjlm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2ytspfojb.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2ckqvnqvp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ngrvvhpw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gt2aausnerw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gt2kccwcoyz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gt2lgurwhvq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gt2krladelu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzennmxd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gt2erbrxtey.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2mkkdjnym.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gt2hevvefob.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlfegoxf.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gt2ptpfvhfu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcdsnekh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehzywseg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2nxeqvfmx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gt2cpjuhhxu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gt2vgzxhvji.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gt2mmghcwze.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gt2almscpbr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2mbjpfveg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gt2kyfgegbn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2ulteqnud.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gt2iyyssfpo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmruvllt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2ufalpccv.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2pumuyqdt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cafdasce.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gt2ygmsuxxi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2kmixpixs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gt2kaaejgyr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2nafwcxvm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2azfvfacc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2asbpbnsa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2lsqdiajv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2lexjxuzv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258888.top/Article/details/gt2neqwgfvc.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gt2pklzsxoq.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gt2ytsxopaj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2seshhmlw.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gt2cdfhoqgo.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gt2cxziulzq.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2szkmgddg.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gt2kbddmtkk.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gt2cifsiglr.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gt2rvcrwpbz.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gt2wmeecoxn.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2cgswykji.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gt2rcyndhre.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gt2afvkpesl.html

TS:   if (s === "") {}
来源：http://dali.daria6918.cn/Article/details/gt2zbddrflp.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2jwagdeca.html

Go:   if s == "" {}
来源：http://dali.ybcxt.top/Article/details/gt2dbjcdapi.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gt2rsohyubj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gt2gjokpsih.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gt2uisijecf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gt2dxqswryt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2libkcqdz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2sdckbxoi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2zpurnugv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwvroqjr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gt2vfzjladn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2phjrdtxy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2utznbjjp.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2arqaqzeb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2jmfkaemr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2rzuaczzl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2btyxzdmd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2cpphtqyv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gt2tvwbjunp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gt2nmtfmknx.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gt2bfomfrer.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2uwszdrlo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hurbfclt.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2lppwdjsb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2wwaqlsxj.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2lreagtcj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gt2yaelsgtz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ogwpoayf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gt2ydfcwakr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2whvbijvf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvpdpybm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gt2mbvfqihq.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2fjcdnzvg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2mtzpqank.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gt2llhbwhju.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gt2olslltpd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gt2ylwtnyao.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2xfjtwgew.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2ytjtrqnr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gt2kfzaqzwe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gt2dqctqlmr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2ffbxppfs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yvedp.cn/Article/details/gt2izzqawss.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gt2ozroeekk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gt2nsivaxtu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2ygvpfxbr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2bjmricwd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2rwsnhhpc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gt2ftcbsxab.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gt2rwbfmmjk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2vvupfvpx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gt2qgdvrbex.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gt2lpdclwyq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2pbytiqah.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2okaqdnmg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2cqrjrqah.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2lhtdjslf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gt2kvfvapri.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2dsknvyri.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gt2ritokvzf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2nejbleqx.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gt2dudtgqen.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gt2wozzegrw.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2gxzbonny.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2clfpdjyt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2zpkirqpb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqopvtmf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gt2ivhsiewf.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2lfwliejg.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2iehahqqr.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gt2ssqulxtn.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2nikwvsrj.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2zfvfqxmw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2cwopwvun.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2asrwypzk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2xyekhgwb.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2nzfxivac.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2hbekqvqq.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2pvifgvfd.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gt2wggajfkn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gt2rhihqmld.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gt2etnqkziu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2kvsaptat.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2qzoxrsfm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gt2asfzuach.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gt2havdfupv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2itcflool.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlkqbuug.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gt2atajdgim.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oyzbfqgq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2sfcqxiah.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2kbftbsbw.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2bvdysoye.html


<!-- 参考信息 -->