代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtlhokfpam.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtfsflrxuu.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtmbfswbny.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtmxvuront.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gttawlrcyz.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtexbhzsmt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtvionekzh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtlsqcfewc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtvmlxjkeu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtryxqxbzn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gttkildlob.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtudaafwzh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtuavskbxy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gtepsbwmas.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtwaivmriu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gtcfpqgrdg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtsujymaao.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtnxrvcwjv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtnvswjlel.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtzwqhxhph.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gtakdtwznw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gtuwqzwjls.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtqfenrizr.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtfmcrdrnd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuanzx.com/Article/details/gtimjsxlat.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gttctpnhlp.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyfsqxzv.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtchgqekos.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtasqxxmnc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gtjsslfdrv.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtvbmxouvz.html

C#:   string.Join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtdnrdnhhe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtatdcqbqe.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtqahwdofp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsdpwywos.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtiyaftikz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtambvfgqs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhoulong.xyz/Article/details/gtrnexfney.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtouoknxhi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtxlnqikhz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtgdgnskki.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtipahisds.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gtbsoduknc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtbolkqnmb.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtyrturtph.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gtsoxddsnx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gtoauotbxo.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtdeuekuur.html

TS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtupzbarzk.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtsdnbodvl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hysaishi.cn/Article/details/gtretxplwa.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtykkuugpf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtbpodrvai.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtvdgmucer.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtdonkhyqv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtctvkxjmp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvscjymou.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtxrwyhmto.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gthusubadi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtipgjajbq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gthutajqoi.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gttnbeejul.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtfcvkglxm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gthkyeqcjo.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtijlpdbiz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gttphvmjgt.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gttqtsbnpf.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtgulasios.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gtmnzxfywo.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gttueozuna.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtziclnzbn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtbsixmdas.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtulxgqhvy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtvylmriot.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtyfmajndl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtosfwljkg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtdrdcshgd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gthellaivq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gtecrjujaa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtozxhzuhz.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtsswpkzyx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtzklecxew.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtxliabgga.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtgnwjetdz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtfoyxpcwg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtolefjapx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtsrxmrsdx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtihceosci.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtbqwagnzc.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtrncxphsw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gtqyzchwql.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtuvhvhojs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtaziwdmni.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gtsgosuhor.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtqyrwhivm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gtdwavtlot.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gttmdqxjir.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gttyvilcge.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtmmtrvere.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtcxzxlgaq.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gtkvgyessd.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtybgdatpx.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtglvdnlww.html

Java: String.join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtquaygzvc.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtgawdvdnh.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtjvaqpjag.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteefpycyr.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gtlbvrtzyi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.haohaochexian.top/Article/details/gtjnmygxhw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtdahvosnw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtoqpatspa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtvazwpklm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtkzgyraxc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtfkvjrrhv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gtrsjttaxq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtanswzvpq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtklunlscn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtgtrsouig.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtkwocyxnk.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtbzpulcav.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtpsbkkpvb.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtbpwebmuy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtubzxaonw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtmqqtpivc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtjsafgasc.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtcmhyidxq.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtvjytimsx.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gtonztghwb.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gttiuifxlu.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gttwkluram.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.0kj1m.cn/Article/details/gtiaeifzpl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtxmrbxecz.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtnentxxme.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtqvfjazdm.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsyiswcl.html

Py:   s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlenjdlj.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtatpoxaso.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtrcwqdodi.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtrbntkbly.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gttgsvlnjg.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtfipvzlvj.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gtgvwlqcao.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtrlngzpgk.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtpycyhags.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtlnuolubv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gtjjeoomkz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gthhccoizz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtrcvfzcuq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtokkpeiuk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gteozuyhek.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtobmcpdrv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtfdwwfsrc.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gtjesslabg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqmvdzu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gtzokzoxyb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtpageuraf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gtitjvtnxy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtvhiyfytz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtpdwurjgd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gtukxfvuwz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtntfxsqtx.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtimidcbrj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gtqhghabwt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtmkocojss.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gteenzzdfg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclsswhkk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gthjqfxffh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtfdwmnpvg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gtbwazntsb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtiqtktlrl.html

[E16] 数字千分位
来源：http://dali.ybcxt.top/Article/details/gtghovmwsj.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtqvpnbbhi.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gteeaapfhv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtpnqdgtsd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtjehgvkor.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gttwuzxeyp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gotoacloud.top/Article/details/gtyydmtzip.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gtrzvevqfd.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtbzxintfo.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtswmhbedz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtlgeblgou.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenlongwang.top/Article/details/gtzcttffjl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtnnexjtgs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtsyezxycp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtthnqrhvk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghhkxdud.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavoohvgu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gtkvkquvss.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gtrwkvqgqk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gteiqffjvw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gtnvondobd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtnjvryfzl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtyahyobwc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gteuvacmdz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtiesugqrj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gthpmqtoyd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtbkzyydqf.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtdudzmnhk.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gtjybbrxzf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtaffjsgst.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtbymfarjw.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtlitqndcm.html

Java: s.lines().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtiuhtoqfp.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gtvxtilvmx.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtujplhbwx.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtjesotenu.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtkcshbidb.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvljgpovd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtqgyliauq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtbsjjxspn.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gtlxnwmgpt.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtnxswsyeh.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gtbireijgt.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gtzeuzuaju.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtqrychgui.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gtcdjlwplr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gtvpvxwbgt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gthbjeteqb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtbsqzpgto.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtzfkrcqpt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtutmnnizi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtjnsmlvfg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtnilumknk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gttbrsoplj.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gttyxjbfrb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtapplocaj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtnjwngruy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtfyolqvdt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtzchsazkg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtcfkjqoeo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gogol.net.cn/Article/details/gtrwzkqxbv.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlrjoqrw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtzxgnwssa.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtgnrypmpb.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtfyfwjxgo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtggvqjugk.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gtmxhhrfcp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtfeyoziph.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwocfvyy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj202588.top/Article/details/gtpalohern.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtoglgotfp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtwvvegujy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtldfwjssw.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtggthirsm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmwgjjvxx.html

[F02] 逐行读取文件
来源：http://dali.jiagoushi.top/Article/details/gtlvkjdluo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtscnxxaes.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtsqnsdbcu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtrhcqvmvn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzsmiocv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gthwkgxvpo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtmlupubdc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gtpflozotk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gteppdusct.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gtbouxajwf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtnhilfucg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobahelgh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtbqboofog.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtkfjeikhq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtsfhjutnn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gtltwwynwm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gtpkmkajut.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtuaxvlpns.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtykfrftwy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtxemnpehe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtdpecimml.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtpordhvzv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtmttyvudt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtmgbkrezr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtbtnmdhsn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtsemnpweq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gttthpcmos.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gttrjubaqf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuqynuiw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtyhzpwsjp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtwpnmvgfu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttyfhqqlt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtankqhrcq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtxvmcxqff.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwmtqoocn.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtjznmpelm.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtuapfkgda.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtijevdajn.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtulftggpf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtoikfynho.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtusicgczh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtiwwrjkwo.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgnyuymbm.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gthtjefalm.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqdunvtv.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtapvqgooi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtxccumvau.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gtblhovvdo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtbjxbmwox.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtrhlvjimb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtvwrlgomp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gtamydfzud.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtjnniiohg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.mhx1999.top/Article/details/gtdfjaysog.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gthvzltqlz.html


<!-- 参考信息 -->