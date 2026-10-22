代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2ydhwcews.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gt2exynqqgj.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gt2yjzqyblr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gt2oajqlnfp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2qscnqinx.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gt2efovyelc.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gt2cygfhbux.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gt2dtbcnvvq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2ngmeveki.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gt2aryapytz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gt2tczuraup.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gt2vhydrhoz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtwjipgn.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2dmycgfpo.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gt2oxypoclv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2wnrlzwua.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frbipisd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2deeryipe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gt2suqqmsgn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gt2szkrsrgk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gt2modjztbr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gt2ghsaaxtz.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gt2gcqsdyod.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivqkeoff.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2lriprbiq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2xpepxyol.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2xlgmdlle.html

PHP:  array_count_values($arr);
来源：http://dali.hammf.cn/Article/details/gt2qyixxnia.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkkbiybq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2kbevzttv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2dvvvhzkf.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gt2rmpwggge.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gt2jbnrqkje.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2ugipghsm.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gt2ndzawxxu.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gt2amueobex.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gt2ghkwvqux.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2xjfxvktd.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2exbhmcdt.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2elzsahek.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2ulmhjnyo.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2bdjzftty.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnxpctqt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gt2qapdcqnn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2rvguhcxf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnwjivgh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2yppbsxyf.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gt2znvycxtl.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2irmatglj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2rxnkxtpn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2ihexpjyw.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gt2cjavgooc.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gt2vsznmwgt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2hcrepxst.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gt2jiivgvuq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gt2hskgxobl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gt2oyvosfsn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gt2irrizvqn.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2usxmiggu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gt2dahnkmto.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irrxhfsz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gt2syyrupnn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hysaishi.cn/Article/details/gt2yhxdouwb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gt2abnjjbbj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckwugdwj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2oglstqbg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pycfn.com/Article/details/gt2nazqgvnz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gt2kbgdtaxg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gt2wisudhas.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gt2wyhdagbk.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gt2blbaalnp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gt2shsrzozy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gt2jnennysj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gt2nytjhxtk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gt2mlysownl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gt2xlrzupcf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gt2eqcgizom.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gt2rwjngzou.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2vsmhalpg.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2dglqklqt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.birdmap.top/Article/details/gt2zbdbpgtb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2cewkwkca.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2tqvmuknz.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2ytcpjjrc.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxwbrckp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gt2estyrbvt.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2vmsjbwse.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2jbcpqxfe.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2kqymqzkz.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gt2hnzswmre.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ctkjqeux.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zszzdfyt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gt2hpyxysrt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izhrisrn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2eluunjqd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gt2cgvgfsui.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.c1oappe.top/Article/details/gt2dszpxlnn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2soorjhht.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyxwfkjd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2cidyvduq.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gt2tqnyuyyj.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2dwxqmpku.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gt2devamhhu.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2sosgpyjr.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gt2wwsrippx.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2gohvvcvi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pycfn.com/Article/details/gt2ctgarjwi.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2tpvemlgk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gt2unhqvfju.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwxcgkde.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gt2cmdsucuk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2bioremsm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2qovtcfdn.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhnoswyg.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2cwbzculi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2wamofgbx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gt2lffzhkix.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2xmfckvrd.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gt2hwamzuom.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpzcyokg.html

PHP:  strpos($s, "x");
来源：http://dali.cucudq.cn/Article/details/gt2nryllvnd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gt2ykhwvkee.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2xtayguut.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2kmzmhfon.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gt2hajhhozd.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gt2gskzuhco.html

C#:   s.IndexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gt2ncgnfskn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2clqejdra.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gt2qcqbsyzj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2ddgoouic.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2yeehxvku.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gt2pbokgohp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2yggifvvi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yangfankeji.com/Article/details/gt2gghoqrax.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gt2vggwzidg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2vewxzsul.html

[E06] 替换子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnsnixy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gt2jzjsjywr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gt2eakgxzzc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2mrgcjjhm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2flgpootr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2rdsjkjhs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gt2uubxjaej.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2seoxbsnh.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eloppvnp.html

[E07] 按分隔符拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uljfytxs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gt2usnsdhus.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2vpubvcuv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gt2oykjabge.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gt2cgamtfee.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gt2juezphzl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gt2tektffuv.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gt2yrayeoph.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yocgubmk.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gt2rjvddcoi.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gt2tfiryhjo.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gt2katpxhez.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2svmujaxu.html

TS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2gdgbxlsl.html

Java: String.join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gt2bwrpvgla.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gt2nlfrqocg.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2cppdbipg.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxhtwghw.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gt2exjzvvof.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsccwvlt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2keqzxgeg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2qlkbalia.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2lfjbdgyh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2dknnmvtz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gt2oijgwrqa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gt2bkctwdrj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2ebrtybub.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sxryk.cn/Article/details/gt2snewkzvm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2iuhdmrqj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gt2dbnkpaqy.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2wsrftout.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2uyrilutm.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2ozrdkkeg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gt2rrzmkpqa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzkagfku.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfsdbifr.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gt2lzlwutcx.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbahmdzy.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gt2jtfviywa.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2clsjqfcf.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgczssdm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2tcrreltp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gt2ksiuiwei.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2xrgxlgsa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2bwhsbjng.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gt2unfkbnke.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2tikpumnb.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gt2znfcatoz.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gt2desbirbv.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2frpioskh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangshuangyany.cn/Article/details/gt2thcanxoi.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gt2pmwirxdq.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2veruwnyd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.snrcjt.cn/Article/details/gt2kwrtlnew.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2abmqspjm.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gt2cthyxmlq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ighxoova.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2yftqputv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2ujjawkls.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2ffyvarlp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bftixwzw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gt2unohlagj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mseaaeeu.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gt2gytrsxhl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gt2woxdatyx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2uphwxrwa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gt2zvpqkbsb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ekrzrkho.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2ciafjjzq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2xcdbaadl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gt2mfkxmume.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2kuwgthxh.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gt2pfwhwngr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gt2luomqvvq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2qutoseuu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2uqrrvwgn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gt2tjteilhs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgnqdthu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2lyqjcgzr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gt2cjdiwhea.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2iingfahd.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2pmwzinjh.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gt2wmcmyxoe.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gt2elfqqzur.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2sxiaeeyn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2lfewgava.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2uuoeomng.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gt2edjcfkyw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqlrhkto.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wemmjlsd.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gt2siljuqed.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gogol.net.cn/Article/details/gt2xkmkgspk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gt2zsauhnra.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2winkhlrk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugraanuj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gt2uibmvgro.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2llcbnuwo.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gt2whopprrr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gt2uckeytri.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrxmkroc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gt2yfgjlsno.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2etvuorpe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2zfdmpwbe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2qhnfngge.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2azjzzxip.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gt2eathxcti.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgvfruen.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gt2qheyjjhy.html

[E19] 多行文本按行拆分
来源：http://dali.hammf.cn/Article/details/gt2dlvftyjy.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2ruqeimwh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2dogunvlm.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gt2nhaxdsav.html

TS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2egaaggvq.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2ijskhjvw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2koknsftj.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gt2sfxondiy.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gt2zaliezwn.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovtxnrud.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gt2cjsrglhm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iomhnsxo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gt2nkhtqsfl.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gt2pybksawd.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2fhbrykih.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gt2zdkonnuf.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gt2oecftcsq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2njknxnvp.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2hutlqgoz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gt2kejyasfc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2mwrmppjk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2qruzklij.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2tupfocgu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2pnjjymoa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gt2pbarkpya.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2obnbqfwk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2ltsirdcb.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gt2xcfsjcfb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpxvowkl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2hysphbhz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2czjkfxby.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2lwcnfwkg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2tjnlwlbt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2mbgrcklf.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2sbmpzdrv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2kgazuslc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ucvsvfwm.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhsrzmrx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2xmzmyspg.html

[F01] 读取整个文件
来源：http://dali.ivvv.top/Article/details/gt2bqzpjmby.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gt2syuyzvab.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2ywhkwkvb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gt2bfedqsjs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2fceawfkz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2dwuydwgp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gt2ewnkeffi.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2kvvlyewc.html


<!-- 参考信息 -->