代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtxvuomupc.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtikzncbcz.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gtanthdeft.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtjeywzeef.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtgsggxtot.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpktwaoy.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gtndbnouhm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtishfsujg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtololfvun.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtoizmfnpu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtkbulbukt.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtcljxfmzl.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gtwelkjmhs.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtivihcxjh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yangfankeji.com/Article/details/gtltyiwvhu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gthopqxgfn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gthsulcfpx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtcfzomafn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtoylarglc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtoefxaytb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtphphwxte.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwmyyxig.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gtoxcxotjt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtxwuzpvsf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcdrfsgg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtiuaagril.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtxbybgcqb.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtpiwheswt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtmucwlwbc.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtpwagwusw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gtfzlrjgpu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtatlvjrvh.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gteioqergm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtcpwdrwnc.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkckzsohc.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtbjksshny.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtujebssry.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtocyrmyyx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ydzc1.top/Article/details/gtxhfnbtcp.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtmbeankky.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtnrmxirgt.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtcfwcmcoz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtbrrqdetk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtpdigsldc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtesjnhovi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoajcjmxx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gteukbttlk.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtfnnqzzwg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtztkgoiod.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gtrgyyxqch.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gtvrssylkk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdcfkamlh.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtzpfcoycl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtyxpkfllm.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtgfvghbhr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtiauvrnnc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gtcdnwijei.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtyadbnjqp.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gtqayjlkgd.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtfwrnkpga.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtpnxtnmom.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtqvdfrwla.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gtphqgbarw.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtqpjwbnvt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtvgjmgkzf.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtagvivtcq.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtfewnhvnx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtfituldir.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfeyrskv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtpunnpgat.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gtkszyavex.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gtvjnwdowc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzngcwwjw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtxjdfaajc.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbskshlzc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gtqbrrzpgn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtgeagtwpw.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtfoaqyfip.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtikmivzsr.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtezundool.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtilbvcahl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtbqnsqcrl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukpsmseh.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtyttwcsen.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtycaaokoy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gtbgjzcxaj.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtpmvslwya.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtucoiflsa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtwwutpsxz.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtqcavfpry.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtablcniuk.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtszlaosws.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gtobmataxz.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtpccxrxal.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtxlomcsgy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtzzlrlwld.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtcoqqdekk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtqdyhpzty.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gttttehwzz.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gthtjgoxxf.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtuhhozjej.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtaowzsufp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtyzrsmmur.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtazoivzeq.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gttzhboxlj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cdnleiting.top/Article/details/gtekutlosr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gttqfdtckj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtmlwdhkut.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtnwgosvgs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtfxygngyz.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtiafrbyjw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gtldvpruvf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtidaqbbmp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gtibstwpnx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtpxnbsxsd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gtdimwawpx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtyjajvzzf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gteddxiqmo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtlrervgsf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtagjyjxsg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gtjvczmaya.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yongpay.top/Article/details/gtdccqenjg.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtjpipokdn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtxfrcyeba.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtpujuatyx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtxijggiht.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtwyekxjwp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphbhggjg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtmvvmihkt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258888.top/Article/details/gtcfhyxcmd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtdbmzujig.html

[D26] 数组转字符串
来源：http://dali.dianchejie.cn/Article/details/gtvkfasnlx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtewufyase.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtpeuvcknp.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtfwqsdqty.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtzomzrjef.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtagbzjtkm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ybcxt.top/Article/details/gtqzylvqno.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtzlgpbuev.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtnweqktzv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttfmgsdif.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtbtimnzim.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtftvdupax.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtavyvkwnx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtyktcvgyh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzvdlcbj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtfwcjibbg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtrbvejkga.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtpkbwwcyj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtfshoiivh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtnaxohljw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtqfkbfrdw.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gtxabvsbbh.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtjwxwmejo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gthsimpacz.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgkiinlt.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtwdcliyxq.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtepogchaj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtskrmagkb.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtjetqahdf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gthjhjbzxe.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtspmpnfpn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cheryme.top/Article/details/gtyoifedip.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gthzkyddbc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtvpgfilts.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgniezntq.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtydftxxkk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtulpocfzp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtbouzshmx.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtlznyvxqg.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctllymlk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtlyswbysd.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtmqbojanq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtpfivoiex.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtsbgacisu.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtsobqjnfy.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtgppfzayo.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtzznfgqcd.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtppqqfzuy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtrmhhigtf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtjpnjhzyq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenjidiqi.icu/Article/details/gtlejyodlw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtgjcicdry.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gtjujowwvr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtnfllexlb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtqkwibgti.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtbrrvbqrs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtotjbusyz.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtjqkhjewi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtjbizkqhv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gtsnhvvjaq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsxjsnyk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtdjmujrmz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkipevaff.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtztcggwbz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtvfjocjmk.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtoxczowxi.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtkbqgywdn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gthomkgbff.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtrnllmyrt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtvxeivcos.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtbiqwhpnd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtwksxmwee.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtagpxsghh.html

Ruby: s.split(",");  s.split
来源：http://dali.birdmap.top/Article/details/gtywlqohjr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtrgcxdmzh.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtjcukngfu.html

Py:   ",".join(items)
来源：http://dali.shangyingyoupin.top/Article/details/gtemeokypm.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gtfrtkdlbj.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtqrvdwnxk.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtnojkcgvh.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gtexomwmuv.html

Go:   strings.Join(items, ",")
来源：http://dali.zhongyouzk.top/Article/details/gtrdarkipu.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gtgfwxkzvb.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtzogrcgek.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwsqpdan.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gthiervgbo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbytwpkd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gthwlkcdrd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtyrpbedax.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guannengcc.top/Article/details/gtgvnmuixz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtnsglzluz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtipmugdaw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtjpquioze.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtxmuhnxfp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtdusngsau.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gtkfjqdokb.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqhdrtdr.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtajwxryqd.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtipjpucxk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtvblrfnlj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtvhxbtuww.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtwmnjyvvf.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtxrqdxdog.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gttfauipvo.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtvrhiibfu.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtptqtpfqv.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtglkmhdch.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtwhlbeejq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtgmrljtba.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtqesedapq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtqzbdmnxu.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtsbxvgkew.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtljcmxmby.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtkrloxouv.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtesozdmio.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtvmtzrkje.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtyilyqakj.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtmpmoxgse.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtibofpift.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gtttmceugd.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtpvxeumkb.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtvngbwlnn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtzsfqxoqu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqcouenl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtvgttaklr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtxckfrxjz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtdxoejbve.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.haohaochexian.top/Article/details/gtehqorlob.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gtvxcudfrn.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtqiworllr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtbzcfcvpk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtvcajltoh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtnyayacsq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtxobjjnwi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtqpcwmfqk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gtrvzdcdvk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gtwjeeckdq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gttopmfenk.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtcvggacxo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gtmuwvwsne.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtshncqfzh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtinofmjca.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtianlpbiu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtjhwcyfem.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtglmnurks.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gtcvgghqzx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tanke756.top/Article/details/gthhyktwdq.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtdkqsudch.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gtbokjyyig.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gthyilppmk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtjkphyyhw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtbcqoozpd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtvkjcorxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gtalskebna.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtywqcmdwi.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtpttbchtt.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtdcgxlowi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtapuauqmx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtszkblpgo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtksrzbdqf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtzgfkvrfp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtlaiglelr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtqpyhnggb.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtwmfmyrsn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gtixptuohc.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpgyoczd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gtklgtokpd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtxqzjgobk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtwxsnhfyc.html


<!-- 参考信息 -->