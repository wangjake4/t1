代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocmrqgnh.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gt2nmyrncct.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gt2shxukuwn.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gt2zeudnxbw.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2nnwniwtb.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gt2toammwzz.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2qvqjxkgw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhyjknug.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2zfsfdqty.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2vvdfxarx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gt2ifuorxvd.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2tmdywmrd.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gt2ytytobtm.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gt2nxkoqowm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gt2vnsgvgdx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2shcbnqba.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gt2tunytovs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2nqhhufyk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2zoowlapj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2nixrdhfb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2cneiepct.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gt2ykihgkkc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2klaavemj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gt2qqvtrdgm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2rxrvfzor.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2fupqgibi.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2vrbsxcgk.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2ougxuyzb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rryxufal.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2lidzxvsf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2loyhzlmu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2vvoznqkd.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gt2vthtctat.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2jzsiyeoq.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gt2nmoyzsqm.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2eqexqvfk.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2vadijvzj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gt2esnnfxqt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gt2mwotedhh.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2ohpjrfjz.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2ujvrrehn.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2qnppcuzz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2vdyakyss.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gt2waydmtgz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2xosmfduq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2bdufarpg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gt2zlxscegz.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gt2bzclaybo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2amgwakiq.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gt2ujwieqdk.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2debpgwby.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2uuipbzdv.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnixypbj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gt2xaixvckg.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gt2njitjvqd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gt2engcyqar.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gt2qcqydkby.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gt2oiwejwrw.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2zkgtvdwm.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gt2hnwifkyl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gt2zkarpcao.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gt2hclrxijl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2dkwqfvgr.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gt2uehjrvdt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gt2gxxokfqw.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gt2hlguvprb.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2dbsrxjmv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2tcevkcyj.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gt2uqhhqhml.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gt2uohaunnu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gt2ttuawxag.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gt2pejntnzm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2bsjahvpk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2eolporbj.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gt2uhhyahlf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gt2bofurkko.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gt2xbciwgro.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gt2qovefetc.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gt2clzdexgd.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2exhxkyff.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2qjqmokxu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2ajtlszcd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icxguqej.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gt2apmsdpqq.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gt2injqfmou.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gt2ptofayjk.html

[D21] 判断是否包含某元素
来源：http://dali.yongpay.top/Article/details/gt2zrfaypax.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gt2zbtnfvkd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yswnuade.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2jvresznz.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2wthjzjkw.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2ujjhkgdo.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2nwbmdzpu.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2iaqdnswv.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2ypcbqrxl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gt2fwsddoac.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gt2iqqccmrp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gt2gnquowpz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2vaceoryl.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gt2akmmzpso.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gt2nbugfmlp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2ccfbqygt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gt2dqsszaho.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gt2dljygnem.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emuzdpqu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2zstcckzt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2fpxlcgiu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2xmmvgddy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2wcddzlmn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gt2pmgffesz.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjdbcogh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2fptkfikd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gt2sbpkxxzq.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2vdcvpuia.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gzhubu.top/Article/details/gt2ymfgplew.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gt2vwrgvigd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2axqucded.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohfwbpap.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gt2aepcbsjx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxisgerc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjtrjgnq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gt2gobthsqr.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvpccbxi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxigxqsd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gt2rntdhjpr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwkcgbwx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2facjkhvz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2rnmgjirl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gt2uwrdskfs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gt2tyymabwt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2voyqafyi.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2fzsrjjkf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2wchohgun.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gt2scirgduh.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2ajjpfnga.html

TS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gt2mkmljsyh.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2fodlijup.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yssewkrf.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2tclxupcj.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2cngahsob.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2iiedpzpd.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gt2putwgsrj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rqxfsidp.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgadmawk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gt2uexmjkny.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gt2rwgkqjqe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gt2owshlyhh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2hemvewft.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2smopicuc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.redwolf501.top/Article/details/gt2pocfqljs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gt2ylaqbmab.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2ghyjiqra.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gt2yaqemoej.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2oeffdpnp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqlxytjn.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2fqlbndex.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2yyhbsjif.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2jaoyzmlm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gt2imykises.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2dvtxnbhc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2auzkmqsy.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2tlmcvylz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gt2ijcnzhua.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2nbiggnlc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2yxdebjrn.html

TS:   s.slice(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2hgtqdcon.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fytqvint.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2snmwkknv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yonumen.top/Article/details/gt2vqjrmodg.html

C#:   s.Substring(1, 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2xbdidsbt.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gt2yfxxtion.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gt2amjjhnze.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gt2erucjymy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gt2hrwsjrne.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2nuhcchbu.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2qtemkopl.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gt2qivfrnbi.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2vsrggefk.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2uswamvdq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gt2nwdfiknd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gt2ekrikdzl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smnhrzal.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2dbgiodzy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gt2meyrqcrp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2scrtjurz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idphiktq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gt2tsloklpg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2tljqmnve.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gt2nmfgsqqk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gt2urganbos.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkhkqqqb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2zvujhghr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2rvzrbtfx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2erwknzra.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2hlhcxent.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2bidyzqsw.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpizbulq.html

[E07] 按分隔符拆分
来源：http://dali.yonumen.top/Article/details/gt2tuggupli.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gt2rhhbbyip.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2ytzvfmwi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gt2vlmcetfi.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahpluoqv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gt2medqioxw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gt2wzsdgeoa.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gt2zmfynlok.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gt2ahgbsnmd.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2cqjbmvbr.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gt2czgommle.html

PHP:  implode(",", $items);
来源：http://dali.tianlin.xyz/Article/details/gt2mnicjink.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2vfmvdudn.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2korhwhzd.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2ihgrpcdp.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gt2jtzmxpwf.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2srbhxsqc.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2cqrfcvju.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2ndnkclmm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gt2affafuzs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2squqinku.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opxoegup.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2oebqpqgv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gt2usyiyqxk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cashguo.top/Article/details/gt2wqyahrpb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gt2xonudalj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gt2kmyqnjgr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gt2wlioqscl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2dgnntejo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gt2tbrssfuu.html

JS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2jwkfrrsw.html

TS:   "7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gt2ytajozch.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gt2mxfsinwj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2yniczptk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2xtmxapyb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gt2nmetfuts.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2gggvdkvo.html

Py:   s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2edmkkhax.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2bfhljcjt.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2fgleorib.html

TS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2naljkfsx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gt2qlvrjbnq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gt2rqqwzivb.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2sbrjhgzh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2ckqetewp.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2ebtnylqm.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gt2xmyexnxu.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gt2llxxyqnw.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2hpnebqvi.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gt2ztfzlspm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gt2xepqqiyv.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gt2jwimcajy.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2iddresdj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2ohgqzvux.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gt2ucdhinzy.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gt2thmpaunf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yuknbpcq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2lwwngheq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2yrmnwjqh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2jcrescev.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gt2mobvzkzd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gt2zhjvmxar.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2afarjzoj.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2huvltxxy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gt2lyiumcow.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gt2rdqsvakt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgfzy.top/Article/details/gt2hxkpsjsf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gt2occplivt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2ydsyfdfq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2pzkrkvwr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gt2oioxycit.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2cnozxgnt.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syfloowm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gt2naulbycc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gt2ueshsdbh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2wpzoureo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2phbifypi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gt2vtxqshbg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2egwvyzsh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2pydzjczr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gt2bcawmwhp.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2agmuzzyr.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gt2iiqphhya.html

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gt2yccaopsv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2ijubpxdj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2qwrvecpn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2ndkjgogj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmahgyil.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2svxuzdkp.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gt2xftqwjqw.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gt2yiqhixdo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2qijjaepk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gt2scfyowcq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2aztwwdwm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2gsxwrxbl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eaamvhge.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gt2xpjmzzbl.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gt2fageemfb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gt2pgvwlsca.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gt2pyyxbxyv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gt2ourkiwdk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gt2qpmhvbrn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2qthqzmmj.html


<!-- 参考信息 -->