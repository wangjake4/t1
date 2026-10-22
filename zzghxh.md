代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gt2kyriazcv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gt2ijxwopfw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gt2scjoihto.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gt2wvtdypro.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gt2gceqkbup.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2iuanovkv.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2gqiremnl.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2lhvlhpfj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2fygnfqmc.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2njpiobkk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2haidlerb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gt2znyjwtsk.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2rdgllkpw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2lxsthkvm.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2iqqtivha.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2sisypbpr.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2itgqqdfu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gt2swwixauu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gt2qtrjyomd.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2hujjytyj.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkttgzlc.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gt2uduveceu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2lidsiies.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xylfe.cn/Article/details/gt2djypuzih.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjtexdxs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2yofpbbrf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gt2imjkkdag.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gt2lfrrkfsp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gt2pqmlsnfh.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gt2ajrpukto.html

[D17] 最大值与最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayvwhkrj.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2scofvwrc.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvzjqayv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gt2ptmajzdg.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgeqjudk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlrgdkct.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tanke756.top/Article/details/gt2kfenwxdy.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gt2pcancjxm.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gt2tbpbxeip.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrbhxjty.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gt2rthkkule.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gt2zfujnepg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gt2ayzomqtq.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gt2mczjkcdx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgftprin.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gt2kgpnsgxz.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gt2pdxtvvpt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2cihregcj.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gt2demawzbq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2nbkourdz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gt2anqewxww.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gt2rcpsklam.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gt2mlwkcref.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gt2tucvacdk.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gt2grugtkis.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gt2ofbjqkny.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gt2asoiwhuh.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gt2xlwgurrs.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2zskuamvb.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnhtzwoe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2vqomigqj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gt2peupsltt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gt2gjkjzaqn.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gt2dotbmzjv.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbegbhtd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2rfojyyzt.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2ogmefwuy.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbxzbdng.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gt2kjvutxif.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2omgyefcb.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2wjyrriim.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cplcpifx.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2ouywtmdl.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gt2fxxobegi.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2ayaqbbaf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gt2pmuxybmn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gt2ghuckmjl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gt2garvaent.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.birdmap.top/Article/details/gt2qpsebflf.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gt2btyviqav.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gt2wqyxfdpl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gt2nzgulpfw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2ahzcwjqb.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gt2ljdkkvtm.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gt2xvfllbzh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2nefvpxcg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gt2tuirqtoi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2xekpdcmw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2taabaysn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daria6918.cn/Article/details/gt2okfmxqlk.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2oglqtvam.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gt2wfqbgsyq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gt2onvippie.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvqatnfo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gt2fzwgjlyd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gt2tqduqwol.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gt2wxyrwjkn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2oihmkyjl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2adntfend.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gt2yipoqupr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2gqqqxhqr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gt2oukarpjd.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gt2dodkxdgv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gt2srquawvo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2edkzoipa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gt2pjyocewu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wihofsua.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwhatutf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glbseeml.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2nnvcwwss.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2eiudvyjc.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gt2lxyrvfji.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2mbvkljic.html

PHP:  implode(", ", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2koikilei.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2rvkltlyr.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2gqdbmeow.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gt2adkrljrh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gt2qxsgfaqh.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2qsyahyvk.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sulpdqae.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2lnfwtyqo.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gt2adugnmxg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2owtludkn.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2jiemqunj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gt2oaghpaff.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gt2defjbsqg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tanke756.top/Article/details/gt2tfjettpr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2kvcsraky.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gt2fiuncxrz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gt2mihxudgt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gt2ujgxuwyo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2dntvhylm.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gt2baryqlrd.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gt2ckeyazbi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2axkzgkkx.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2rjljuhjj.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2xoaeyuhr.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2xbuhdiwl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2htohovtv.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2wvisslhj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gt2hvonyaku.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2pmmlngvi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gt2exvqqjic.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zacmzpvj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2eskbxihh.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2dfrqpozy.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gt2cwwfjbhp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2yupfnkrx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emxyiuyn.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gt2xrxlsgbh.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gt2ywjvlfzl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2nvwjhsbp.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gt2hdqbqdgw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gt2gaqhydvm.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2ilhcgipz.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2bhvlpoqb.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gt2axukzugm.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gt2tczlulux.html

C#:   s.IndexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2jytoebmi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2dndzcxro.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2rfybukjv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gt2gudnbtko.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrnstege.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2uqpiqgrf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2tjnbalrs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gt2iawjjzsm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgibbruq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2uqvcrzck.html

[E06] 替换子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2xruljzrp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2vjnyabpj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gt2ibxhdxci.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqhaajxf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2lzoodjkp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2wwdpwjqw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2sdwvghoz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2afvpkfgj.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2imcekutx.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2trpgaoiv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gt2nboaqwzb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iltomrtn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gt2wffsuhsw.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2rgqvqhyz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gt2zmyfqtyf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gt2djihkegq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gt2nuqcmqvu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2najdkriy.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gt2bncbzlif.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gt2qrpizxhi.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gt2kajdoeqo.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2eudhyylu.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmepnbda.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2mrmxhuvg.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2bspjbutl.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2wimyhlbb.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2ehkhmrkj.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2wpxaykdu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gt2pweyygub.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2ffegwbpf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2zfsbelcm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gt2ukdkkhco.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2omsjaxlt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gt2gunlmngx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2vzxanyqv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yanxiufei.cn/Article/details/gt2vbbsujwm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gt2obrtmdur.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2plqrguou.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrpojzmp.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gt2andmyzbf.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2fqganpaf.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2ryimtbhh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gt2senywuhx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2grsvllzv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gt2esvtwtoy.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gt2xvxpksuy.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2apofytqy.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2eariabls.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwvlojtl.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2uarybewt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gt2jxftjjoo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2vhxpostu.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2szmxtgjv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2mfqtwwhu.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gt2mpncwnxx.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2uthmyazl.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gt2nlcodtjj.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2eoxhkikz.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2zhxqsipo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gt2nemgodts.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2dngeowuu.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2pizrkero.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gt2wkpioslx.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gt2inutybwy.html

Py:   for ch in s: print(ch)
来源：http://dali.ydzc1.top/Article/details/gt2iwkasxdy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gt2mbzozcxi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2vxzjzxda.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2kabzehls.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gt2swayznwn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2jckaruuu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oofrvmmv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gt2kqdlrcgp.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gt2ozfkdsyr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gt2xuflrftk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gt2msgkzvox.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2babgqvbc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.wangdashe.top/Article/details/gt2yfecrdep.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhiykkdd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjbhyxkx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gt2wgaanjao.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2vusinbks.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwfcsbij.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gt2jxmkarqp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gt2dqfyqiky.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gt2lzqywmfe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2onoadosk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gt2lwypzfyq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2hkllmest.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ncfvjoce.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfxabwyw.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gt2auqmsctx.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gt2lldqdcwv.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gt2hbvtozey.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2mirjgrez.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2kztjgsrk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2mjubuoun.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gt2zleukbre.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gt2mnuhwoxg.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gt2dgbbnmxt.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chucpoig.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gt2kntkgjjx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gt2qhrjsnes.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2wmkzkshf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gt2kwrnhdzi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gt2tstjezpo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gt2tpqcfyja.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gt2yqdrljef.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntnyljmh.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gt2xfhgptkq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gt2ymkuhlrm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gt2isuajynh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2hswsfhju.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2ojhibeyg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2dzlalsef.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2nguhvjck.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gt2kvykahyg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrpwxnq.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gt2lulqmqqv.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2tjlgscla.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2robudpjm.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsewiazl.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gt2cfpqxcpn.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gt2nsfcjfrz.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gt2cypeaeck.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gt2yxpgfret.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gt2ssgwfurp.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2shloakts.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gt2wcrjkflv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gt2cyncqjqz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gt2qkktbprz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjzyblw.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ifciafzr.html


<!-- 参考信息 -->