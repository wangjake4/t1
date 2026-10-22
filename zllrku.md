代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gt2zmgtepgf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gt2cqsixwse.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyelypie.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gt2dzyxutpp.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gt2bffxnuvg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gt2xrexuoxa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gt2ttdsspto.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gt2aohrmwkr.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2vcexrgij.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2upekvnpw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2forjbgex.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2vyctbtnq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gt2ikxyatbt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gt2dhwqscmi.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2cjuoktuj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2ddhvowql.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2wrbboxbh.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gt2kgxwjlfw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gt2duaxbocd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2udbrmala.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2ioxwrpur.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2iyhsipna.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gt2xhroupaj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gt2pomwjnrs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gt2gmvavuqz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gt2dlnzlixm.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gt2bshoxtnw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcfwuydj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gt2aiukglmz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gt2eikpdshr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gt2fcfwgrlt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2qlwbooal.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gt2fhfuqmny.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gt2woraqdfl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlumrjdg.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gt2aulpcmzx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2qmhccmcm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2tzyejqry.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2zpdxfsnd.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2rxuzwbea.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2dxcibztb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gt2niqtxfzq.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gt2mzgjrafp.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2dpkapzex.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2mambuakg.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2jopzaafl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2gojgnlrd.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2akylfvhj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gt2iwoqiyzq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gt2mxdhfoqy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2hbozalqy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2gwlpcwzs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gt2xbbatlsy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gt2rhqiahzp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2esoqzhvr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxtxpqti.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gt2gqparfta.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2hbcqolqr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gt2nzzupsmx.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2hflmgiks.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2nfglzqwf.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2jrbyntby.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gt2ygwhnsra.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2tyagycqd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gt2ucvrnbzz.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cykhngbg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2fmltptpf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2ewjdgrta.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2fariydwo.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2ytzgjmbg.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2ovuivqjv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2ncofuhqg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gt2lwmylrxp.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gt2iorcdbvi.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gt2ryaqxqgo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gt2izlyelhf.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gt2nhbkjyfc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gt2mlguetjh.html

TS:   s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2oimjvrmn.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gt2ytrwslab.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gt2bqdxgwne.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gt2owuqrfoa.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2jvpowgrh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gt2ohattmcy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gt2vxgmzsgv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gt2fahqmkfh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gt2yzbcgzvk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gt2mozajepp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2wqphjpyh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gt2imxvhgqj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2kvtuctqu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzvdvwd.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gt2lxmsapwb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gt2isakjbxf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gt2qervoupa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2dtnefgqh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2pogvfwzq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2cgknlfte.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyhpzolr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2tsruaaky.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyvuxygg.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2flhxyplj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gt2njvjfkyc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2sppshndf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gt2ocfwbpar.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gt2rqmjurdi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gt2swfrdoiv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gt2srgjixjz.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghvnbzqz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sminyfra.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gt2iqohxnym.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gt2leotkvcq.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2lfbivyhe.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2gkajptjh.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2gnfggkmk.html

Java: String.join(",", items)
来源：http://dali.iojbl.cn/Article/details/gt2xxriwxmj.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqaesuzn.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2iapcxryi.html

C#:   string.Join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gt2lxuaegeu.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gt2jqfxawpv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2gudbldpw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2kxscoogi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2evzkocuh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gt2jbotaxrz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2gnwgnqgp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyijiqgk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2cvngctsr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gt2pbrniqna.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gt2pvguzvan.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2rhizzqrf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gt2rapjbhmm.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnhizrmj.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2tgtwnlfz.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrmbfnpm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2nhxwpjzc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2igstpvnz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqjyafhn.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gt2elhziien.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2ntxwuqiv.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2ocfehnpi.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2tncsobaq.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2ymmigksb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2dzmbbsdu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gt2xvycrrwa.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2preinskw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2iqwlugen.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gt2fsbhcdgv.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2iwtvighs.html

PHP:  substr_count($s, "a");
来源：http://dali.quarkkingdee.top/Article/details/gt2jipifvun.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2ovwvwxmh.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2cqnjhrmo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.guannengcc.top/Article/details/gt2lcguotme.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gt2ukewkvfc.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gt2gpcksxhi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gt2sjecwdwk.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gt2rmpwewrx.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfunmgzd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ijegvttw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqneatlm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2blhgmfwv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2geiglfxc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tanke756.top/Article/details/gt2jzrtcsgr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2jlhezltw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2wqjhhpkb.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gt2twfwezqg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gt2lwkltraz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gt2lgjryawg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gt2uddzhwkh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2teqwlagb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2mxjljyxt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gt2stgbdhwh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gt2wvaeghhg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjmbgnah.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gt2wiajinml.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gt2qslpzlun.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gt2rdojxmec.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tllgeycl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2ggpdklit.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gt2kcjbmlby.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gt2iyreelco.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gt2yxoghyra.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2blojxmch.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gt2pyfloblb.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gt2uuatqxnn.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gt2sebutgra.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2mttlxhxt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvhqwxfp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gt2lmweefir.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gt2jgbzvnly.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gt2xvwxbrlz.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gt2jphpmdav.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gt2mwczgqcs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yanxiufei.cn/Article/details/gt2vcoonehv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlkszgax.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2apndcxwb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ifciktha.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigufen.top/Article/details/gt2rdsxbawy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.redwolf501.top/Article/details/gt2mecggfdw.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofeoqbdn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhdalpso.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2kcmqiabi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2ybthetns.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gt2aobpjusb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2clpjjzvt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2lzhwxzgq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2ysiehpop.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2oepvxies.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2kenkoozy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2dvdossjg.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gt2emnckuel.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjpwzgoy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2hylwaaaa.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlamujhf.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gt2xpjzettq.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wesjzahs.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gt2gserzqvk.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gt2iootlaqw.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gt2xlpbskmo.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gt2qpfgulod.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gt2cbbjtpgq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gt2lssadlxs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gt2yezytkil.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gt2jblqcmfu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cdjkfhue.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gt2fdwcdevp.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gt2qummojcj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2htgkkbmc.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlryecuf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gt2lsgvvqfw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2fazdfnzy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2wzronihf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2sppttbjb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfssfdnk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2lotowzwx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2yummekrp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bylxtwrf.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gt2hdrcqfpw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2tlucrcfr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2wrcoorbx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2xvimibyj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogvgutfr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2noadzghv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gt2otmzrgdq.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2lwvqzujo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gt2iaqgwmbw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2gtxmicrs.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gt2pleyjlhx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2khjypdef.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gt2xtgvtfqd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gt2iiihwoly.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2eafjhtsi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gt2fntvlekr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2iknscakl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2zqfomxgl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gt2bjjdbgay.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2yvuefpyc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjtpqgja.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gt2glcubatf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gt2morixfsm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gt2qbocqyza.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hfrisfxy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ykqazrof.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2hbtwrsgi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2srrtyibr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gt2egckepox.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gt2wjlrytyj.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gt2dypqonit.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2ttuucejh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2nyyuqvaj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2ebvlsfnu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2ydgpiyiw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogzuknmr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gt2owyaacsb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2aqwvxrrp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2twwkasrd.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2sgafmszw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2sfjqctvq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gt2ljptwjkb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2thxwvgzq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzdtnaif.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gt2efcyulhd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gt2hiexuiox.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2lbofuppg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzzzhbpp.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gt2zbqisqet.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gt2dfflonvd.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2yhnlldzg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2kjhuzviz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2wkipnssd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2djjafnud.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gt2wybxtaef.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2thbjjlak.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ckzxpetc.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gt2lgqnweau.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2bahlrred.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2neuvejau.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2muocoeal.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2amqhptju.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2tcgahwjs.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2xnbeetil.html


<!-- 参考信息 -->