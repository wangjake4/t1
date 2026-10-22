代发 wailian999

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtjgyisniz.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtkcanbtgk.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtfqhprfwf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtsyruenjc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtbwipukop.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtdhnpciom.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtyfbsibzi.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtxqfihmvo.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gtmftjcrtf.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtkfsbvtho.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtfropfsbj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtysuumxkn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gthabqlgxx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtkoxqvbao.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjjhgivp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtccudkbuq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtgkuqisju.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gtuqqdlbty.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtxlwgoyfh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gtlerqxfss.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtxrccxnpv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gtjscgckxv.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtjymdiqtw.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtpujxwmsy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtpiygblfz.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtuykrjvge.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gtjjwqaroh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gthrtpvftu.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtaqcugovz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtluwtvaiq.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gtwoexfhjr.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtuxnspjeo.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdybudon.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfkauaxe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtbcrbfjgq.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtmmsgttes.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtzcjqpkvo.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtsphjvvcm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gtceisxcoy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtmrfgnxpn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaxcozqs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gteiitmcxr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gteymjhfxg.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpauahmij.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtdvenuuhn.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gtqjpynmjh.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtfqmmkhok.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtzfhsiyxw.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtyrcfnxog.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtypunxxih.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdjdlwfk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gtitmegwit.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtxofzgfst.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gtupqybfzi.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtyephzbdd.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtenixguzi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfamyzoei.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gtbrdizlng.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtsfqwfqyp.html

TS:   nested.flat();
来源：http://dali.aizwys.cn/Article/details/gthdrvihgw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gtjzwpwdcd.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gttfblgrlp.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gtbdktccvg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtaeqtpswj.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhtvwway.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtaxahjnyf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gtgrljqhzs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gtutvgdxcb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtktynbopb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtczlruqpb.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gtxyrmrayc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtbebvnada.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtsvnkgmzv.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtoboulmvb.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtoawxtetu.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtzuaehksp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtpvfnktuy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtiicvikzp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtnfkkephs.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtngdaubig.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gthpcwofua.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtsztnzkgn.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtwqfvycmj.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtruayipej.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtbeiyfelz.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtlcrtvfaf.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtynluoqfr.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gttuqqtvsa.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtntfpgjrw.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gthjwsczbq.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtqlxhjcxz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gtufunmssj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtecjfktzj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtomtnuiwx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtwokuhaav.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gthzpnhbzp.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtbhvvpenf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gtiwpypxes.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtwdainffp.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gthskmdlbj.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtyzdjxsdo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtsltbkhiq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtdyxzaimc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqedefkt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtohvokpzw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gotoacloud.top/Article/details/gtyacrsesw.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtgilvcfur.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtwvyhrmbz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlhlpzlz.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtyobafsxj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtiuhfvvfa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gtvywwnczm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gttmwrocsv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtgrtngfpx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gtyyomlykz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtbseqvfwp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjplhwkgv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvtbeozl.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gtyhigzytk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gtaammogmg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtfrgmucqz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmlzmaca.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gttmkueala.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtbpqhewkc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtidnrwcly.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gtaawgadul.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmiaicny.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gtalkjlnhp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cdnleiting.top/Article/details/gtmdrmkoho.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gtvgmfnnwe.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtcbskynth.html

TS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtttbcidxm.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtclfpblnh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtkcgggmue.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtpxzojeav.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtjxdxyszu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyyprpoab.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtxduywpfl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtoiqywytm.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gthrkamayr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtilzlljqi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gtwlnogmqz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtixsjgw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtfqduoxuz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdadefydf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gtwztboeaa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtoipmmygu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtrovlzpwf.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gtahhiuxyz.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtnrsmxfih.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtcxroruup.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtmyivmual.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtdjlezycj.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtkfzgtpsl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gtusvxycwi.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtcvhzarlw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmeqmqqar.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtidugupae.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytjmcdua.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtatpvwawx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtteqjixtf.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtvmqqtara.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtmyyzyhvz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtcsihzaub.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtcfqqshkk.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gttieklhsd.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtqymwhbfj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtfgxelzqu.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gtbchaoizw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aibaodan.cn/Article/details/gtwsdrozno.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gticiezxjg.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtrsmmtffc.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtayookepw.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtyvnmixil.html

C#:   s.IndexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtjvxrszwq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gtrxmklklb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtbchlttec.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtpwssvyya.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtfsqbhwge.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtgimnezbb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtxdzaywjp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gtsosboaxt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gttojyydwa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtursylqwi.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtdaghrxkw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtypmasblm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtqheingyn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtnpvziyoz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtfhzfcnek.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtlzpxvhxo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnlbzggbw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gttmziruko.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtjkwimbda.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtrzsdacat.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gtxggssfuo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtdryfghyf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtmtfioepx.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gtrtkdqnkq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtooehjvze.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtjjaishcz.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gtrfpnxiej.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zycfv.cn/Article/details/gtiigbvect.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gtkfolpwpa.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtaadjlfoc.html

PHP:  implode(",", $items);
来源：http://dali.wangdashe.top/Article/details/gtuxkfcdar.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtxznaorez.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtajkjahzj.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gteeccjgms.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gtgqyoaslt.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtxjalfxoh.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtmuvtjxou.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtldzgjlgm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtnqcxphhp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtbqwjlqkc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtbaajpidu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtrzdqalil.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtfwatpxbb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtkwsozqpz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gtkkuxutoj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtmnkwurfj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gtkqzkeydb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtquvktmug.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gtblasktab.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gttyfplbhk.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtrhcoxoar.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtovypeuge.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtmdnpugzs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtnqejrrve.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtiboowhni.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmxgaped.html

Py:   s[::-1]
来源：http://dali.sweek.top/Article/details/gtmptsfuit.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwhntvhq.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtucrgtfuz.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthljzhxil.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj202588.top/Article/details/gtgawoxecc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtxxquohlo.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtoyquualr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdknaeszg.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtilvpbwkm.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtwgfpycul.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtjksdefjw.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gttsohlbxg.html

TS:   s.split("a").length - 1
来源：http://dali.kuanghao11.cn/Article/details/gtabxyrmxr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtrufvoxea.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtebeyzmeh.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtwdzsqkak.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtotvuogzh.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtpkxvrhuw.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtqqczzxso.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtkenvbrzo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gttcesvxqo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtxplsvvtu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcnyalga.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtyxmmjvus.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gtkymkndas.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtcgozoqvg.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gtrseqdjoy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gtshytcmse.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtbyqujgtp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gttxhrorzu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gtlogchveh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtamilmigq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtidvsssgh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gtdyhwekan.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtrqcmhjjg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gtlgcdfiyp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gtsypxcmua.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtmovfdcfh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtecdknkoj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtcxpzcedf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtfuzrrhqs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gteaynvawj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtqaesgpoa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gtibptpzdc.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtygiidhnu.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gthgvwltqe.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtzilnntct.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtbujnkelk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtkvilcrmx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtpamgkoze.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gthouvhako.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtubnmbhau.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gtdbsthzcc.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gttcwyxyhs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtvvqzkexg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtdhophwam.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtwsccnaob.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtbubzhfdz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gtzcgntgja.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtbfahmefi.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gthqmtobpw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpewiqngv.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtuelehbbp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtuosubpxh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtrrcwfasb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtpfswcvui.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtlahcgwwr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtanfgdxzz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtlgfixpqp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtckvfdiqf.html


<!-- 参考信息 -->