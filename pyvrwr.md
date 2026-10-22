代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2bidovbfu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2qlxeerqt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2ucnlsoev.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjfigbbd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gt2rvothigp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gt2vgycvwmb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2yqsgxkua.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkofayry.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2bxbxeifu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxzednyh.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2zlaekiau.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gt2iixqnwkb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gt2tlgevmhy.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gt2dhpmmshc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljrmwooy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrncczdp.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gt2snafljzr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2gpetgnep.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gt2lhdpbqcq.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2meetekvb.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2nexpnghz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gt2uimktpjn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxsbnnni.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gt2ichtytia.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gt2qqkthtup.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgxpbwd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2lsczyuew.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2sgdwndbb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2vlamsqtm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2agdklxqk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gt2rvvmhapq.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gt2udrihdev.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gt2lwgndiac.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gt2ydloegjo.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gt2bwsntepd.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2fuczzmyz.html

PHP:  max($arr);  min($arr);
来源：http://dali.316326.xyz/Article/details/gt2nkqpqabu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gt2dmoywohv.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gt2bzfscszv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2sbclktty.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2owffigtu.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2kskdtzje.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gt2leechbyb.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gt2izgktggs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gt2bllhkotn.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gt2gcnogjym.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gt2nyxravlt.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2vfglutrh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2prlinlex.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gt2bdnlgfts.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gt2mswvpqhz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2dnqeliao.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gt2bbachspt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxkypasv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gt2tfqxanue.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gt2iftrfkxr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gt2vfpouqvr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gt2rfhiczwv.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gt2vazppdrm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gt2ekyejkxw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gt2gvkranhj.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2jouwvzuq.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gt2aiwazvea.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apxtjift.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2yfwcktdp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gt2kzwgzwno.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gt2hrcaifhw.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gt2bpqzxgcq.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gt2tzbsvxbb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.316326.xyz/Article/details/gt2yszdboxt.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gt2ifsewmfz.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2xmgbklqy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2agcaijec.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2zioduvqg.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2brmexguq.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2pdequxxy.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2vpnzyynt.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2eoakryxp.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2hlxokteu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymohyuzh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gt2zehvwzmm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gt2vzuhmkjq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2tbwsaaqf.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gt2vgeidwpo.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gt2virichlo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gt2dehttmiq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gt2zvurieyz.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gt2hgjmjqhc.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gt2ijlzxhsa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gt2unmkpzjc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gt2qjjgqhtx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gt2nlwmdacn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2fcauoznx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gt2ttbeayla.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxinxjrm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gt2wsfjezfl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gt2zuvoofhz.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gt2qvzgernw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gt2dtyaytjl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gt2jydxkwgf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2azzqrqbq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2drkhvovl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gt2jmxcpidm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gt2dxxmgcza.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gt2vvxbcqvj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gt2aiuhlqnx.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gt2qfdtjwih.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tian-w.cn/Article/details/gt2leeebzkj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zejihdia.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2xxjojcjn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2vfkphtcw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2qvwglgec.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gt2lxfgcutp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxnguryc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmqgalfn.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2wpfzmcdi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ivvv.top/Article/details/gt2lixpkicp.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gt2geseuftl.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2vbesyrrz.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2cvtuvbzv.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkaujzgf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2vyyutxye.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2vchhgzad.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2iufxmuir.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2sqocxgvy.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gt2jnwldnks.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lskcjzho.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2pffocinl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gt2congrxsf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gt2jxeepiuw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2blzqclmx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gt2tehkhagr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guowangkeji.top/Article/details/gt2hphmrmgv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gt2yhoyipyu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gt2uqfowecs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2aawiuaih.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gt2mtsyqtes.html

Py:   "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2ltmngwpc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iphzfzwp.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2pwuwexho.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gt2aqxstkhu.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2jzxnvtuj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gt2oaefluor.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gt2qxvobwdk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gt2stzwfdgk.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2adfggbho.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gt2enhnhrws.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2dacaxwdl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2oonruvbu.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2agnbqviy.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2nasjqnyb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gt2sgbavzwb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gt2uwugrfrp.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gt2wdtntptf.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gt2adfbazcg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2phjfezlp.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gt2xadkrlau.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gt2sfyazbde.html

TS:   s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gt2drzsdakh.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2zvlrhqks.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gt2koegpeuk.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2cexhvscu.html

C#:   s.IndexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2xofitoyr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2auirozfa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjdatkrs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yongpay.top/Article/details/gt2qoxybavg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2musutdid.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gt2vdzeojgl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2ukntrbqq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xziqi.cn/Article/details/gt2fouinptd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2sptgwnxc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2ygbtrdnf.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gt2manqptvj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2auxbxqze.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gt2axvicdtg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2ypcdlpvd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2lhsqhoqy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjjyzhdh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2gfrszgti.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcirgkg.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpuoyqn.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gt2jnkhttal.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gt2bafzlstx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2vyiebwzk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2pnnqtynw.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gt2yiadkysm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gt2dstzxett.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gt2enjkwrhk.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gt2hrusqews.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2banihywp.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmlqgeqf.html

Py:   ",".join(items)
来源：http://dali.nanxuanxn.top/Article/details/gt2leklrgcr.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gt2kscgxske.html

JS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2uliyquke.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjgibrod.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2ahpazxox.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gt2lkchbtry.html

Ruby: items.join(",")
来源：http://dali.yuxming.cn/Article/details/gt2bhavnwid.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksybzssc.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gt2wzfutxzp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenlongwang.top/Article/details/gt2augsyozs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2vbxamjkz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2vfvpjbpz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2hcbkvxco.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2yikwqfdt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gt2emwkkgeq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gt2gmfeagad.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gt2mwxmfhns.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2hytqpzwo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2igjnhbbr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gt2gpuycvec.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2ietvjshp.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2mqmrdngo.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2dndjynkn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwepvvdr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2ixwqfbrn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gt2mtmbvhsq.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2sypmcofl.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2xwasenns.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2jcfkwzeq.html

JS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lndxsicc.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2spjibjfi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gt2ugxiojuc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gt2anndbpik.html

Ruby: s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2wlyutsxd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2lhmizuiu.html

[E12] 统计某字符出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2yozhvafy.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2xkvrnabn.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2trrpfnbz.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gt2fowlvfgh.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gt2hkbkdioa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gt2hjvhfpua.html

Go:   strings.Count(s, "a")
来源：http://dali.0kj1m.cn/Article/details/gt2xmppfqwu.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2cooyfwrt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gt2swvfdfnq.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2nhxynerx.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2ydjuyuzb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gt2tthjkehn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2occhllrx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2dsgkrzqd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqeqcdju.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gt2rhundysn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gt2gclsshvm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2rlehpxur.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gt2fwqopget.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gt2frqptiwd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gt2uhgiyexf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gt2kjqzfmtu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gt2zrqyahvr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gt2esjguhsg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gt2vjfreavm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gt2lkjzpojv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gt2fntllhcd.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gt2ssbkfwex.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gt2dxqlkszd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gt2cjonyilm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2cmwpmaaw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2qqxbcgkz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gt2tzbieitc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jianghu66.top/Article/details/gt2ooqvkrtc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2dogzzdfy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gt2sbrqdcme.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gt2gkuorzdt.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abikwdko.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gt2gzwbvgpg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2tbjsllwk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2nqfxvtaa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqdhcxeo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenzaomai.com/Article/details/gt2sezmfyej.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gt2tnqsbaaf.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gt2pnluoqcz.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2viflutcb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gt2jqqdwnao.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gt2rvjtsocv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2dnszcstp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qipjcont.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gt2czewzmwq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gt2xlsymzqi.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gt2aqdnxbvt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gt2mzhogzwk.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2lryhdphv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2ttbaybge.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcrkoyhj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2tfkxngun.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjtwqrgx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2gdgfjrau.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2adqsqyum.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwdonjlx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2dgevdnwx.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2njnamkid.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gt2uqjnpyhd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2npayitcj.html

JS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gt2hzmlzopk.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2bsndbgxw.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gt2wzpqooyi.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sllwjmuq.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gt2kylhpblr.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gt2qbibdzen.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gt2ozktqgbo.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2beeuyals.html


<!-- 参考信息 -->