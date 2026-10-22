代发 wailian999

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2klbgjjgq.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gt2kmvuuvmf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gt2jjsxbruh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xinyue.icu/Article/details/gt2gjkmzqjl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gt2mrsgprln.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2pbfqakfo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2evvtckjz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2eqfxpkvu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2rkpojavi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gt2xdqjaaih.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2mlhwvlpt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbiztgma.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gt2xjixfycg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxewoayt.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2phbbstdl.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2echetpos.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2mpsnsukx.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktznxoqy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2acwlisbg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gt2zkhtiahy.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2tjzqeuzw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2ibfobyda.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gt2varttppu.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2ehovlrcs.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2eowxyxco.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gt2clbkckdj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gt2lfweuazk.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gt2kdxismpr.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gt2mdinziro.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gt2itejqusa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2zlkscicx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2faudlvyn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2careaace.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2yijslude.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gt2qwgsnkyu.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gt2pkgkdvsw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2heytnjtn.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpxxzpiq.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gt2msaonvqm.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2kdnsaidj.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2rrryvtjs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzybtzxy.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gt2qpudosag.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gt2niuglqfw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2izzaamtw.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gt2sigpzgyb.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gt2pebtuoef.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2ydvbzlkm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2spcnfyar.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2foytwydq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gt2otnrdvje.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gt2jxeunqxa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2aynzeczh.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gt2xkydwlcb.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gt2jtudbjsn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2ccygdnzx.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gt2ctecvhyp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gt2fyglcaip.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gt2vwjtmnlc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gt2xaccoipq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2gippolgr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gt2cxqvrmgj.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqtiuhtq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gt2eyxovsok.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2xaayobfm.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gt2byxddntt.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gt2epxgtrhb.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2rhrssbna.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2cvxegkjh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gt2samhhzqh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dflvbuup.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gt2ytnpxwpn.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gt2ehfliysl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gt2mxnecttx.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrwsrmsv.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2ptqyulms.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gt2itotgmrg.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2zlpuzuxe.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2gwzhkdls.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spwhpqbs.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2emodankw.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gt2lymxjoyi.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2mkynngvn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gt2iyfdmfom.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gt2tcfevsfm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gt2tnzwnmtp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ftwaphpr.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gt2erazrojq.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2uwffpajj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2zekkmwei.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gt2qimwtmgr.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2fmaxdonb.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gt2groorrdx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gt2wzvafluk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2lwazelba.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gt2ywvuxejt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gt2jtmwathg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2itpxpejf.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvfbueat.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shangyingyoupin.top/Article/details/gt2euosljry.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gt2bogcpxuc.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gt2oqqmolak.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoaynia.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cqqwz.cn/Article/details/gt2ooqbrgrc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2vrnkejun.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2xannouue.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gt2ftuzwfvy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gt2dbwxzqje.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gt2pkkrvnvk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gt2rsftljct.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2wyildwhi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gt2zdhovhzs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gt2psaeipom.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gt2xxkiokac.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gt2zulusnfe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gt2rgziifza.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gt2ocmfrlcl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gt2qcmyesjg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gt2gpgxpnpf.html

[D26] 数组转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2aqqsminv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2dlvntrxn.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gt2vijozjsa.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2mxiorref.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gt2jsmzikoa.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2fjkzeeus.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2ympkwgvz.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kghogiob.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vstesprg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2cnatrfcx.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2glzerkpg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rriuvcpd.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2afkklzje.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gt2wifubeov.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gt2ahvardwf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2skvcafnt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2klbqazdc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gt2hcbqiigu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gt2msljhshh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tglhukkb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2tizxmvgc.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2zehxfjov.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhuxvcbv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gt2ikjhobec.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2tbqwcmht.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2gnssnkgg.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwbfdquh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gt2ywipnipn.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2fchmqdqw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hysaishi.cn/Article/details/gt2kaqttuvl.html

[E03] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gt2ipkhnkcw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhixingplan.top/Article/details/gt2ubyrifvh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2nhiipkyb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2oekcawqr.html

TS:   s.slice(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2morvcbxv.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2zpjclcgv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcmjwbkl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2mcgmawuv.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzndfxa.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gt2muquleow.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2ppxjeodf.html

PHP:  strpos($s, "x");
来源：http://dali.zhoulong.xyz/Article/details/gt2ycneojgx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2efmrlpfv.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2dybfzcxm.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2ksofzqzm.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gt2psxrppbw.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2ktggehmo.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2ldsromdn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gotoacloud.top/Article/details/gt2eqxhetrd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2nfchqvoc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gt2mtnwknov.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2yhyrdyqc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hammf.cn/Article/details/gt2wjjkhihg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gt2mutqveem.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gt2tqvuusni.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gt2obbskveg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2mfcaczco.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gt2krjfzcqg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gt2tqsiowwn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gt2inhpykxm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2yunnkzew.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2epdgriqn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2adqmeosn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2jtaaktqo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmlgtomy.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2jrxrecki.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gt2fchdzeny.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gt2gpsalngr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2jftexslm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gt2krbzjeaw.html

TS:   s.split(",")
来源：http://dali.yj202588.top/Article/details/gt2yqrkxjku.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yongpay.top/Article/details/gt2rryfimuh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gt2kdlfelnp.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gt2timcease.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gt2loaqbwdu.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gt2unqlzwyp.html

Py:   ",".join(items)
来源：http://dali.zhengqikj.top/Article/details/gt2qegvnfqc.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gt2pktxnbkw.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwhnqmxv.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzjcjdoc.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2bppbiyib.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bswavzck.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2goagejxu.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dehoomrl.html

[E09] 去除所有空白字符
来源：http://dali.cheryme.top/Article/details/gt2ovgyuxpn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gt2eckvmqwj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2jrcsjvlt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2wfrpgknv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2dpfzwyor.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2adbbstgw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gt2sogpspbf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gt2caxidweo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gt2zftgwnqz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gt2ckslnojk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbmwnjkr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gzhubu.top/Article/details/gt2vutuimbb.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqauoahp.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2wlxixwxs.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2cdccpygs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2mkidgelc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2bemaavdh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gt2lxbzqmyf.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2wmxidrdf.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2ygzixnhv.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gt2vgufnqzd.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2tmslsugh.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lygdcuwk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2nwbzfeyo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpafpsoo.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdfpyncp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gt2vqogmlwj.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gt2uqazmxbg.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gt2yaxywsup.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gt2jhgchvgg.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyvsehqv.html

TS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gt2hpswcpqs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gt2izrrqhel.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gt2dbdsgtep.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2rsyahvkq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvgeyygr.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2edicpnbs.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gt2voiqimii.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knxtajyg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gldqkqvq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2trywsxll.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nurtttfv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2avplgamc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2iuvtwrbn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2xnfteggg.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gt2aapublzs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgtaubfo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2nxdiagsg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gt2hnmmpsgj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gt2hzrcdoeq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2gqvkfzrt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gt2pnbwzkrw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gt2sowcaifc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2pfiygsjd.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gt2lqpkqkgz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cfmjqddq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gt2pzhynwfi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gt2rkcmplbm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gt2fyqvpuyn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2nveflkua.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gt2wsaiuklb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2urwkleix.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gt2krhrfzxf.html

[E16] 数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvdnwkyn.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gt2tjnqwhna.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gt2jnsablbb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2iwwrvarb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqnxduko.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2ukggndhd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj20258888.top/Article/details/gt2jrvlmlan.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2umcsqlnr.html

C#:   1234567.ToString("N0")
来源：http://dali.tianlin.xyz/Article/details/gt2pyujwida.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gt2kmjkmgin.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gt2nbccwbzu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gt2bhjxbiar.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2qqkshfwu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2nskzahbl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gt2wdagcfmt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esgbwztg.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gt2hqqsknyk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gt2bnsourzm.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gt2akmvkvdt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gt2iymxiwau.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gt2nosvirnd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2bruhuxxc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2jtcztafo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2ltiojioi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2evskpjwh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2bxoxtvwc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2coyobtrz.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gt2ahzoxzhu.html

Py:   s.splitlines()
来源：http://dali.jinqigfzy.top/Article/details/gt2elvtpidb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2dwllvjct.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gt2uyalupib.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2frwplcyd.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gt2ksddivtl.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swcrmlhc.html


<!-- 参考信息 -->