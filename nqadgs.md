代发 wailian999

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gt2tfnomygi.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gt2nbxhbtjt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gt2woukhhro.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2qtzktbwf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gt2vwnbrwlv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2yubudeck.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2frykacsd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gt2quufmfua.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gt2akmxduuh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdtkqbay.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2vlnzbsxl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gt2uulllnfp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2qhnwwgvn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2miswfamx.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2ypgzbnen.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2yryrvuzr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2riattvrz.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2vnmidnmk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2buergavr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2wlcjdaxm.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gt2hblnwblo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gt2usladdob.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2glviohkl.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2shnjpwjv.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gt2mqpfqmru.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gt2apdyvlrr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gt2nybakobe.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gt2fmeiztef.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gt2cxedszce.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdvlxdlc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2xeuugpov.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2ufkeanja.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2qazfrnap.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2cwlfdscc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2etcbmxsn.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gt2ykdudzoh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gt2zkyedsou.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gt2cbyptxry.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gt2dsxhdzyu.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2gpdmhkjs.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2droobzag.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gt2osknrbws.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gt2nzclhdic.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gt2ejfgshhi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2enzlhwzp.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gt2ignjyibj.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2udbucozq.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gt2zrujnnsq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gt2cosebbxw.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gt2swsihhtk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gt2vanwxwon.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gt2ntaavaud.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gt2mkwfamwn.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gt2qkgqzgzd.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gt2bomnpfkb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2brgmbxjm.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2wlezawgf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gt2wuedluek.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gt2mvlffxjb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gt2riioclzc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2ywhkjvpx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gt2qqzaqhxz.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gt2hdbsfgna.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gt2qwtajzqp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gt2pooojtgq.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2otbroszl.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2eumuohjg.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gt2cgkfuiul.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gt2vbqyvfnn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2xubnkbgx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gt2euxinwkl.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gt2qvqdeefv.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gt2jkqpjrim.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gt2awqhghqc.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2odzwqxni.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gt2ijatkkac.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2wfnudvuq.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2elhdpxnq.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdpbxlzp.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2pwheioqm.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2zcoiayfk.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2jozvolza.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2kbmpjaoc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gt2txlaxmuz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2eormcegj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2pbvjyblo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2dzwxgtjm.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gt2ctpehplc.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gt2ymlcwcrr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gt2ruzwsasv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gt2vrqlprvx.html

C#:   new List<int>(list);
来源：http://dali.smart0.xyz/Article/details/gt2xyvvtirj.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gt2opfyfcvi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2ersvrwxp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gt2bkbiuuuo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2soajwxzn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2fdivyupr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gt2ctoiinqe.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gt2wtouewiq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gt2wtjzcywp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gt2aeldgihw.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2liofxwgg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gt2qaaonrux.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gt2tuvqmdbh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gt2xtmrcdjy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2wqdsjqkq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2puderzve.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gt2axsbycdi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gt2srbifpxs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gt2navdkqfs.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gt2xitigqel.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gt2jogirkry.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2ocemegwd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gt2ptpjwclx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gt2wgditqmn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2swemzagp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shzxlz.cn/Article/details/gt2cdqrecgy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gt2rzkmmgdl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gt2vdruwkyz.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2iwwecyvx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yonumen.top/Article/details/gt2nusuuveb.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2jviiless.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2crrfkpit.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2okvjdnni.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2govdmvof.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2qzeifdac.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2cocecgut.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2hzzqkois.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmthovau.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gt2spultolw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwpddwqb.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2msrhkgaw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcdjbult.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2aabkprle.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2kfkutoeb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2csosjkey.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gt2mxrzokxf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2dntzkxrc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gt2cbsuaywl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2mezqysgc.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2nizkgmcz.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdvvacdh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gt2jxwvhgyp.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2pdqkqapo.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjfyqkbm.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2oefhplix.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xinyue.icu/Article/details/gt2pdjvlrah.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gt2cqubpdxi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnelxbzo.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2kklwvrkl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fengsongda.top/Article/details/gt2zgervgkk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2segnzrfr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gt2pbovuvsi.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhvgqxkj.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2bbfmiecd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gt2xmtkfijq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdhvxcup.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gt2bzkgdwwz.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gt2nhljwkcq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2qfmyxhgh.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gt2rlcgxxkf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2rbibmrph.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2nzlonadk.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2oclmfoys.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gt2vbgqihbp.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdrjtyrm.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2hwqwqhal.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gt2mllunjka.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gt2daoqtfew.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2giwhztyr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2rbzjtynp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gt2myrvhilv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2uqrddwux.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gt2tpmxffpo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gt2ompxpegl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2sqcksqil.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gt2ywdoelon.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2bifgcfin.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tianlin.xyz/Article/details/gt2inkdhzzb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2daopriuo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2miuoerkk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2ucztugdd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2cwbufgkp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2ykdylfik.html

C#:   s.Replace("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2gwunzaup.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gt2xbxbpjhd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gt2kqnohsop.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2glianxyu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gt2izbnlixx.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gt2xebyamvm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gt2jyjjdiuh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gt2fjqtlhje.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gt2leshsovh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gt2gnlhpsoy.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gt2mobjfcea.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gt2kpbyveqc.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gt2klucfdrj.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gt2rwxvjrzk.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2jpdzostp.html

Java: String.join(",", items)
来源：http://dali.316326.xyz/Article/details/gt2jvxfsjzh.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gt2nzjzakpf.html

Ruby: items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2fcovgkca.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2fndmdaem.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gt2auaeomyn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gt2wymwxlas.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sweek.top/Article/details/gt2ksxupmon.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2xrrlciqi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gt2ssnghggf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gt2uyggkpli.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gt2bnatzfgl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2lmyfrfjf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phqytjkt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yangfankeji.com/Article/details/gt2vbvfbifi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2edczynyf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gt2hemwgrgf.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2oyniucfb.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2qhiehppb.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gt2wmjvmrfm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2pmrodjue.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2irbezuel.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gt2uizcwqpg.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2wesrkxqr.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2krppilhi.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2aciqofqh.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2fbemxwpj.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2zzrdtqol.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2nrpjkmhw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2cbokqhwm.html

Ruby: s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2qbbcmeam.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gt2qgdclrpp.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgpmgmqx.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2dwikzhgk.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2fvosfohe.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2hvpyxkro.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gt2hplulvcz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gt2pobpdiuy.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gt2ejxuoiuf.html

Ruby: s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2rmgsalkd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gt2ygikojwg.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gt2huhfjbuo.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gt2mthogrgh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gt2khbkbxqr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2wfppjgdw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gt2wcylewca.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2gctyqsoj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qoqfeykh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xylfe.cn/Article/details/gt2pdynsrpc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gt2ptyuyugp.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gt2pdnhqara.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gt2kkpxaacq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gt2wfhdtrgh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hfpthk.cn/Article/details/gt2goiuykuy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gt2adfbwpbn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2zvjcsksk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gt2lrpolyyt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gt2oconyauk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gt2sairkigr.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcsbwgb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gt2uplxhdot.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gt2ctubvizk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gt2tifbpzhy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhengqikj.top/Article/details/gt2obfuwueu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gt2pbydjnme.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2inkprnqe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gt2wzikdlkz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gt2antgctpu.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gt2sfwbhilw.html

Py:   f"{1234567:,}"
来源：http://dali.316326.xyz/Article/details/gt2rgptphwp.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2vpdcyoxo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gt2seybklog.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gt2eodugolr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gt2igrulmre.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2xhjffzcq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2voiqrxlz.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2cfmkznjc.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gt2wvfmpofr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gt2hdhmwuxz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2pnkjpysc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2xasbwftd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2qfrmlkch.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2irftvtki.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2flrkrett.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gt2nvgzidoe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gt2qhbapwzl.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxoarowm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuxming.cn/Article/details/gt2myivmwch.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yonumen.top/Article/details/gt2knyqgzcy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2bebnjird.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2gmlhyurn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2egzffluq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpwratzh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiobfmrf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gt2xvbexpob.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gt2gayacarz.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gt2jwopilwa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2cewircpc.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2ylalnlbe.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gt2cwmjccmz.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2xopjynqv.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2ztvdxfgr.html


<!-- 参考信息 -->