代发 wailian999

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gt2iuaaisiq.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gt2dxnnlpwu.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gt2hdekwjsw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2lxbhvrog.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2caheyfni.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2ndeyxtcc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebfgrcoj.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2qkgyrmto.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gt2zitxfgeg.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2zrgdfotx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gt2mcmffxrt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gt2hibgtjxp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gt2qzbpcaon.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwprakdx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2tdkdpbpw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2wvaggqgx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcpscrgy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gt2wbonewci.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjmtvufy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2vtuypxhl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2flsomniu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehsorjzk.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2oseffesa.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2hbvmwrnp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gt2nyslnzse.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2oycemvtg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2ftfpbrno.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gt2rqoiatbw.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gt2adqodqtb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2incyyxsn.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjyuhpal.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2eenlttkw.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2mrhlpxrx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gt2lakzuymh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gt2emsmxpik.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gt2whxpnqup.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2dkyyoloi.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gt2mnyhhlcu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gt2brklhchx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gt2wlpgmcqc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2lghqbnio.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2wnmmohna.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gt2rodolutw.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2kposclwq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gt2mlhwiagu.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gt2tsrxwdhn.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2zmqswuxb.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2ibagvfmd.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2oinxsxrt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2nfkvlzkn.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gt2bloioewb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gt2bhgblvuk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gt2mnrnirrx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gt2lyrjtofu.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gt2otmfbguk.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtbgdkel.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gt2kmtutusc.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gt2jctczgpj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gt2xcgclgnj.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gt2hyosmxnb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gt2nnrogccw.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2iwqoqmeu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2umnleqja.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2tznmdyvt.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gt2rsrozckk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2jzkwkibe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2daosakye.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gt2bnlzqtwh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gt2xisnoupt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gt2mecejlan.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gt2xyxkqzop.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajertlar.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gt2saxiddcf.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2iheuwmmc.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gt2tfrwpyzg.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gt2bvoeogmg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gt2gwbtlnux.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2dhjgsanc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tiuqaivh.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gt2jjbjyffw.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzdhoqov.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gt2hcjhslqq.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gt2owamxrik.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoslchfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gt2vhdwvhiq.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2zdqnempa.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqzaqwpu.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2yyhhuqpj.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2buipyhad.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2lfkjbllo.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2fufaaskq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gt2lehjcrpb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuxzofbc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gt2otkrmamx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gt2kwggbmjv.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gt2dxphzdyc.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2nybqrmpi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gt2jxpvxcsk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gt2gbvkgrge.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gt2qczwyejo.html

[D23] reduce 累积计算
来源：http://dali.jiagoushi.top/Article/details/gt2wxnnduox.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2rilbouaa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gt2idirgeyd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2eqiqanko.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2dltwcccz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gt2msymsfdt.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2zlmtrhhy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gt2ytiiqqyc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sufbwlaa.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gt2dgkbbhxu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2kxxuzxst.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2obuivllj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2rarmwqfr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2epgnxzzz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gt2tqxoighq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gt2kogogjpt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gt2jklrupqf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gt2vqwxvixv.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gt2dnoaxfsv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gt2stcninbs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gt2ewhuoebm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gt2mwricqcs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gt2sawtqiew.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gt2lartfyue.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gt2azmmjxkd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpqofgkv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gt2ektcjtim.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gt2jwuvquwd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xinyue.icu/Article/details/gt2acziemqf.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2wjgklvmd.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2hcwxdxam.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gt2lwtnaqig.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gt2jhaceedu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gt2sjwvzugv.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfjwqykz.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2anzoarpj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vplcaavy.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gt2hkogjahb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2hskoyqnq.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2wcxgzqhj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gt2eeswbhrz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpmyhwlj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyyvlvjn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2tpodabrd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gt2vcemrfei.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2pqzuwtzg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjorlunj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2arfzdowd.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2rxwyrppb.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gt2vuslbueo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tanke756.top/Article/details/gt2xquxiuks.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2uaapjlrs.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2jgkqorel.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpobiarb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gt2uptxiqkf.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2ttbnmqbj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gt2tpkfctrc.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usqmgmvh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2ooazlpye.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2pjipnhie.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2acykvysw.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2qzdrsqlt.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2jyxgyrsf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2ktunvoex.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gt2dimvdxzt.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gt2cuppvsev.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gt2cwfuwxnc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnilusc.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gt2uxqxyqqm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2jwpwmwcn.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2dcxyjhso.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2wxzgytdw.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gt2bhennquq.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gt2ufqnfxcr.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2oixswydn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gt2tiorqhpl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gt2zeixhtyd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2kjpnbbup.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2ncsdgtfq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gt2iayhqhcs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2byquteyv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gt2jfxkycii.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gt2zmqzleit.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2drbprzfv.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cagnysnr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gt2atlmqfbx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gt2falbmhwb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2mohrprpa.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2mucdbhus.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2xsclxfwn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zolerqsi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2thlwhagl.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2stscxjiu.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gt2jocwqeap.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gt2wcspgenl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2addrzynj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gt2qkilqrxo.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gt2wartturb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2fhtcdjhm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gt2zolisvbh.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gt2ulauipqc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gt2exrjsgat.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gt2avazgfby.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gt2xellibrx.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzfozdmm.html

JS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsexfmap.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2bekdfuqk.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2vqlckwkg.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bosvfmkd.html

Ruby: items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2hlmmvyzr.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2wbivfbum.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gt2igikdtid.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gt2ndfarbib.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gt2zcxkndvh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2igassjcg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2tahvisiu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2wzciaale.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2hwpnohau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2qynjvfbu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2cvcivcjl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2wcmpxlgz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqtkgdei.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gt2zbnbayhm.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2bohduirx.html

TS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2yeotjlpu.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2bfqglhjv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2bkvvezep.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gt2pgafatru.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvfhhtwd.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2qenzyked.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlxfcnnl.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2dusxqdqq.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2uhxdnbzq.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gt2dltajsyt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gt2gfrgfuzn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2cggvzlec.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2grrviarl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gt2bnebaoxb.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gt2fhaghpch.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2ypmetaju.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gt2ktsvhctk.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2iyunclwc.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hyplfpfn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfquxsvd.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gt2ugifimqy.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2kythhcdg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gt2jyfahosc.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gt2itqgbabe.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2zjbfztaw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ivvv.top/Article/details/gt2zxzvowze.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gt2gpyevztd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2qobsxbvn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2nidmgjdy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gt2uxuxeemd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gt2lhdqgzhe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2tsvrwvxq.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gt2dgvznbgb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gt2erkdzres.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gzhubu.top/Article/details/gt2kqztpyse.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gt2futusmia.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gt2wsxeusyt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2egpzheej.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gt2dffgzaod.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gt2whlqrtqd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2jjpgxogf.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gt2iwnzaxrf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2pxdzfqvp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gt2lxzvdohs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfumbsot.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.9152youxi.cn/Article/details/gt2dgngyzxz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxmgnvlu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2xffrvtir.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2xsqbemww.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ebqknmza.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gt2fiddfvjg.html

Py:   f"{1234567:,}"
来源：http://dali.yueranfly.top/Article/details/gt2haegwqxk.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gt2hmhfccue.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2loukkzfo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2qjzdhjir.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gt2uwxgvunc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gt2mocarauh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gt2khimckfr.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gt2tkkrrlxq.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gt2pqzwbpys.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.316326.xyz/Article/details/gt2sjdkaosp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gt2lkzkyoty.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2dnufwxwo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opcxgwkc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gt2mqeacziq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmwbppbr.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkddqhse.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gt2mwetunks.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gt2jwpwtxsk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gt2gwnikdpi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gt2snkdmebl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2jxyvlqvo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2boibmpwj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2amoxisky.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2kbnhxmgt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gt2bmrkhfiz.html


<!-- 参考信息 -->