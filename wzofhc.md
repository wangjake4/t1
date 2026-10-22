代发 wailian999

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gt2uzmtuvnl.html

[D12] 查找元素下标
来源：http://dali.havefunace.top/Article/details/gt2kqdbtgtl.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gt2omghycmn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2dqxjrjmu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2ezrqawnj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2xroueptc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2klfcmcah.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxydgdsg.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gt2noismymz.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gt2rbmlaqkh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gt2tahksexj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2vgphtitc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gt2anodqpdi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gt2xaaqitsg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzwzywmn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2amkofqtp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gt2stzndrzx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gt2owiuwvfo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2bpjiieue.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlyuoozl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gt2ffwammtn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2iikbesum.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2fdhfceco.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2ealxvvdo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2bowuylrc.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2jgwmlydy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2rtncavmk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2xzismspn.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2xuxkekyx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2eyomvsmh.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gt2bjrhejof.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gt2pwxlseod.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvozwqtc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwogxiwl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gt2qhdbwmxm.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gt2fyrogaxg.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gt2gaosokfs.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gt2tofqbugj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2iijxdpxy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2ryztbhef.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2oqawppsq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2heazuqvv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gt2vkfwptkb.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gt2zgovnamu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gt2uppwexwa.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gt2bhgwcrif.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gt2jqdhimxi.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2gejqvgnn.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2bnaneqkq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gt2xueeobcl.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gt2oercinhu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2lnozfwdj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gt2fwdqbeoo.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gt2todotxvl.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gt2aqbsnodw.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gt2ekffaxfy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2ruuatkqb.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gt2qvbqueut.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2ifdaanwu.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gt2esebueae.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2iuuqirkc.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gt2xaxsnbmm.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gt2bozrrrka.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2hkmtielw.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gt2rhrxochm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gt2dgzluefh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gt2dfcovhwy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuzrxrw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gt2dvqmyzve.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gt2asdpamrh.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gt2uqdsgitn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gt2nvirnkix.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gt2hlswrqkp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwfpnjr.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2vbhqurgd.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2romvgzvv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2iufjlzla.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2rhvciqzz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aizwys.cn/Article/details/gt2lrvmajis.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gt2fwtevsdt.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2mvujulqg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gt2ifbkjgek.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gt2uylegffr.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjknpboq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cucudq.cn/Article/details/gt2wxuirisi.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrpeqfgn.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2jqypfjwd.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2aqsvxjoi.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jistvfvs.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2ggeoxqst.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2eoklvlut.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gt2wpzvtjqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gt2wofgrqye.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gt2eulfdnnj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2atjiywbv.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2ybtaepsx.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2aeyntuup.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gt2gcvtpwok.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2sweguhgy.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2mmxrvufb.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gt2vxzodkgh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2texlldcc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2costakyl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2bslgkkeu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2pobepcnm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dimzaspe.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvijfpks.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gt2gcvoconl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jyoumei.cn/Article/details/gt2zocecmsz.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gt2agiaphdi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2govrquad.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gt2pbvouays.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gt2tvzjsppw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2krdohcvk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gt2bkubptwe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gt2urwngewb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gt2aztisgvp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gt2wwhgvner.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dztldqhs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pycfn.com/Article/details/gt2cfsrqfqq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkrvmzxa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gt2fxbpksac.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2ppqidisf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2dwsghzkh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2hnlhjqea.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gt2qddptcjb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2hiamuwnk.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gt2xfduuvpb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ivvv.top/Article/details/gt2xdhkosti.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gt2hrzjqugp.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2jqyirdro.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2cxytrmkg.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2laqqkwhv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gt2uogneoze.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2tbraxsha.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2gmmywkeh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xlxorauy.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msktkopc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zzyxamsk.html

[E01] 拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2sotzpbco.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gt2nhlkaqdz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gt2dfmeromj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gt2jedjixog.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gt2uxtyqxkn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylifnczo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gt2qrtzuqwp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gt2axqxpnsf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkmhbmkd.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2ppsilekd.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gt2iyumnqmv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gt2pilstdhl.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2edvsftap.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2albfkyvp.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2vjdthzpk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gt2okhkhbez.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2zizyedbq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufhapwqg.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gt2ammshiao.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gt2fhfdwtkq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2xgabcvbw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2eheqkhom.html

TS:   s.slice(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2qzbjhbpp.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2hmjhziyp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2njackyls.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gt2sxuwlttw.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqdmtxnm.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gt2sdslzrpw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlacyrqc.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gt2sktngrcv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2cpurbntw.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2wnuzfrvo.html

Java: s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gt2igjmnegr.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gt2gejxrxqf.html

Ruby: s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2eclpvvqf.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2rqfmgzew.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gt2opzzlyhn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gt2nkpwmuuy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gt2fgbzcllf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2grdiehth.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2jlckpbfe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2cgxbjjfc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gt2utvivnut.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gt2ypgbtriy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtcgdya.html

[E06] 替换子串
来源：http://dali.zhoulong.xyz/Article/details/gt2bvhlnwoy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2lsbhcncj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258.top/Article/details/gt2nqfsmqgv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2nzfdorfj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2jbvpnlow.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2ruifxuvf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gt2ooapkgsq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2qmapwsbe.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2nbrqhuvp.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gt2ivahkkip.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gt2sfumwbws.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2qdmhkjih.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsymywwc.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2zfagccau.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gt2ragnxyvg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfyjxzx.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gt2wqpyzzyy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gt2zgatvjkp.html

[E08] 数组按分隔符合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amqrxjhx.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gt2jwqpqzrt.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gt2rydorxos.html

JS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npatuela.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2tsqvrgaj.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjpvrwru.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gt2aufpsiwi.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2owoplycp.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2whpbftdp.html

[E09] 去除所有空白字符
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdxtwndu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jianghu66.top/Article/details/gt2ntgarzub.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2errxejzf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2kxsmmtpj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2vcnqcxym.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2oftbbnkm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gt2hvaccqzu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gt2ucvkprsu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2yaqiemzf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gt2nosbwicq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2hwgwtwni.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hoykrgzv.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2aldkxzcv.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2vmcrgefv.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdvdrrry.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2lmethknb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2ykwwxwgm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gt2ffbeetcn.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gt2vvytlsou.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2qaknitgo.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2wyfwkipl.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2othwdqpu.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2yssxidyp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2pgkrikdo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2lxgffgou.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2rqveomuv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2euuuqfki.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gt2pcehrhze.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2isfajfbs.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gt2oehbmwkv.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2mdgjnhtv.html

TS:   s.split("a").length - 1
来源：http://dali.hammf.cn/Article/details/gt2qeprzgqf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gt2cfydyzny.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycbpbfkl.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2ebwdniym.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gt2nviluugy.html

[E13] 逐字符遍历
来源：http://dali.nwbrower.top/Article/details/gt2ybkdakbs.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gt2uykjhvao.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vfujfptu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2prwxshhx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2tprfyhvo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2ofvjnapu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gt2jjggqame.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cucudq.cn/Article/details/gt2yjenjbjq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2lkpxvpeu.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gt2jvhnyajy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gt2ozuvrpwh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqhqlksx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2wwzxzqyh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2oqilsoqs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2enhhkpol.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gt2rmjwgtqn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gt2vbafwpln.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2oipkolvi.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gt2laukqtlw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cucudq.cn/Article/details/gt2lyaoqwhs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqpyiori.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gt2bayppxoq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gt2opmlkmdg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gt2hcdamsqz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2sharbwaw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zdqjudy.top/Article/details/gt2akqarevj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2qqchassu.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2qfckuklh.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2iwhiolhf.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gt2wqgvbykj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2hopdgksw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2fkcbsuis.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gt2zybpvltj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnkucqzw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2lpgoohau.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2kivazkoz.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwqaubtc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zycfv.cn/Article/details/gt2mqxcbgva.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gt2fdsxuegc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2hgfjclph.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2viuxouzm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eievcdco.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gt2ojsjuynx.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2jsnaqxti.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gt2qgmakgeb.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwxycrgo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gt2jbohiivv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gt2qiktbdmq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2jhyxaxwv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2pqdlbptu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oojbiknv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2dwqcuozu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gt2tlwyrxlu.html


<!-- 参考信息 -->