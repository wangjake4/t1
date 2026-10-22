代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vopdsbdx.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gt2assrkpdk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gt2mjpmqjch.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gt2voopnfkf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsjgftmu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2sgcirpvg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gt2xvmxyknm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bilvryvk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gt2uyqhvoqx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gt2iwzpqhdp.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gt2usbtbmti.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2nluxobkm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gt2dnwkslpf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2aklymgcf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gt2gvphvsoc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2lactnupp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gt2lcnnrbtt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2uzywjvje.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gt2rlknbxmr.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2ggofsial.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gt2qptrsdgp.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2svtacoyn.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2srvvthho.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2auvfmgte.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gt2lwssnuxx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gt2milquyzi.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2hkvlkbij.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2ucbizlup.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2oqgcdflm.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gt2itohkjev.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2usriqvmm.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2uwlkoerw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gt2mpismkan.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gt2yqxkcpbj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2qsmueltg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2yoijxbsh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gt2sdjfdhtb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhttbrry.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exyjsxib.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2rnslegnt.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gt2mzpaaxrd.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2cpakkdhg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2ayulephh.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2foaoqmyn.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2upzlvahh.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2lrsntxul.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtkfcdoe.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2atjinvbp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gt2ulhhykgx.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2mdqveugo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2nugtejwi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2ifogcnar.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2izoktgsy.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2gcznqunm.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2tjtqtbpo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2fvsbyjli.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uynkuhns.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gt2uduayvgx.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gt2epfutntb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2dkcodewd.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2kdvrdrew.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gt2rwgqmpiq.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2fyvbfsaz.html

Java: s.indexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gt2rlkwvarx.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gt2iwtgeqma.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gt2fltvrldl.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2uwmhdsnc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2tzmzrnmp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gt2awnvknjk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gt2nnxeyjnx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2cfhggosm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gt2dvssvmmm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gt2qoxqcimf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhongyouzk.top/Article/details/gt2pdrrqexb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zivgxnso.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2cmlqbfwg.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gt2tpabegth.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2xavkqsrw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gt2aznbypap.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2pyjhgrvk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2folklwfu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahaowwwk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2bpnrjvye.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2jnvcsuca.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2pcphdyxg.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gt2zdyvktsm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigfzy.top/Article/details/gt2klpyfhie.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2lomnqikt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gt2duljoigb.html

TS:   s.split(",")
来源：http://dali.shzxlz.cn/Article/details/gt2okhyewmh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gt2wrfrdafh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gt2qodiyedm.html

Ruby: s.split(",");  s.split
来源：http://dali.cheryme.top/Article/details/gt2aactxnvb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gt2mhwxfyuv.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gt2mznoigtj.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gt2idlzrrfl.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gt2xaahqpne.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2hdvhfgqv.html

TS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2qluadwaa.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2egswdhtp.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gt2jrhgfrbt.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2ntkovbgm.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2zwekhmxg.html

[E09] 去除所有空白字符
来源：http://dali.ivvv.top/Article/details/gt2foncarwm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2wckvioje.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2nzckpaku.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2hffqcrti.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2nnmcsigt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gt2ajzjsbhc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gt2jzpaevoy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2yqgimqmy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gt2iaqqwlll.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gt2crbhyiuu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2huavvmeu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gt2dhvgkauw.html

JS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2uxxkenpp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odkrgwoc.html

Java: String.format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2dckccvis.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2wjulacvy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2ijdaxalp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258888.top/Article/details/gt2fvfdbuus.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2fqnzpeli.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2gurzhkcp.html

PHP:  strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2yfpvmpib.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2tfsjhorf.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2ejluidwj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2tkfmfmlx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlvlnwsh.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2axyqtrqx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2udqleosj.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gt2qbzzkevz.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gt2lgwebvnu.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gt2auheobfr.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2ucopwyme.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2aayifezu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gt2zexjxeen.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gt2upupzonk.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2cbvtupam.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gt2kqfgnafv.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gt2rhpwytlg.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gt2tsqqaiad.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gt2fkgdtrps.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2fhohjsjo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2weexqwap.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2xgohdiqv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hammf.cn/Article/details/gt2abyfgqbu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gt2izdqyfpb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmysaghd.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gt2inczbxtn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gt2zbdicxws.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gt2ulbqoeyd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gt2ogiqbuqm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gt2sizhxkgk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gt2dgesnfwd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gt2qwllusir.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gt2yulhpfea.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqnchjvo.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvlhibml.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gt2tsaqwure.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2yhdpxnai.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipdjfziv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbyrdtzw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gt2rfbuaibn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gt2ocbnwfpm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2wkvtmmnp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2buxqjorl.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gt2oyczzzbo.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gt2ltxnhbma.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gt2qtjoacjo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2mrzzkbjk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2okaqleym.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sweek.top/Article/details/gt2qbkqxutx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gt2bikradgz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gt2kswtngnu.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gt2eftqoybd.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2dppllmrq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gt2gddznoxm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gt2hufeeptk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2stfalfot.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2oyzbjceu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gt2thgnvwru.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2gtnjdsot.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gt2bxdxwpcw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbyanjp.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gt2ujsjjern.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gt2qmmwcvol.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gt2ghfpvjlv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtrrivrm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2pwuqzbjg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2bjofvdyo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2jxvdcvlw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gt2rclbxcyd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2ooewgdxq.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2dztmyohs.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2lwdwhkpg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2ggmaekgt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2ugcgyueb.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2amsqlpwa.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2smyajqji.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyuaityg.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdzvtffe.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gt2jrdhdfac.html

[E20] 判断字符串是否为空
来源：http://dali.xuetiantiany.cn/Article/details/gt2atsknjlc.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2dbuttbnt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.snrcjt.cn/Article/details/gt2lbrhngiq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ktebcvtq.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gt2dvqfjrxd.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2wfxttfxh.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wigtivsb.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gt2zygiodfk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gt2cnsaxqke.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gt2cpfljtum.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gt2gdopsquu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2eoglyezv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2zzojhlsx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2dsbzpxaa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlkbkbxd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gt2vuxfdfqc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2muinulxq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2dzwdjhao.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2lefnfmpu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2scjgnuel.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2dkbexbfr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocjyvogn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2ahkolvtk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2lrtfuzqp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gt2jptvvpef.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2rghufcct.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lweaukxz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bglwgysv.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2oymkceml.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hlebibbl.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gt2ymvwgddv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fejwrmsr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2odrxwrnu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gt2nqujeybw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmgtuhsy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2pxflixrn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2dktbtglr.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qiqowfbp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2nkzheobx.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2aqbwcflk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2uttfnato.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gt2hsqcjpsa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2dnvobhca.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2lnxtcsve.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gt2xabhplzn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gt2nowwaokr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gt2qbilemtj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gt2pockyxye.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnnxkapb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2byzrkvdp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2plhkuwpa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2klkzxzfd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2cbqjiigh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gt2rzwjfdba.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gt2enfyiuxo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2pubplwkd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2hmgdonxl.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myhtyzui.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2dbglxcjg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gt2ehtnpvsh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2gatzvnne.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gt2odiyvicm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2lstswrqy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2apjqckrf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gt2kmqxwrsa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2tfgmemte.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2kkkakbzx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgalixkv.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfxtifhn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2pxmgwnub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohkysdfh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zojowznz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2tbsipcie.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2tmerygyu.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2bvkweldk.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gt2zrikkylr.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2icbkrtvx.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2xditemvr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2xoitwqnc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2njbxuzrn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2yajxqqwh.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2tndfqfdc.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2aoulomtl.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2jlecgcsm.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2tnjungti.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2pkgslles.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gt2tnbjjvit.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2vrprixeo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2dwltorfs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gt2ywpeuguu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2sglbkmxb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gt2onbqnhtc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2xkmhhzlh.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypkyrrnz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gt2gqsbaepm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gt2tyjnzelx.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2msxfdnre.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2xajcbigo.html


<!-- 参考信息 -->