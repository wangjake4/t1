代发 wailian999

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtfmuxhihk.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gtiqhoeyja.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtyzctuekg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtxeymomyn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtbhrmoscj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtmtxmvxkx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gthvsssyqf.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtnhgovmcb.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtphxkeziw.html

C#:   list.IndexOf(x);
来源：http://dali.316326.xyz/Article/details/gthovkckje.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gttmutubya.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtdqcgucsz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhoulong.xyz/Article/details/gtygzwfrla.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtltshuqkm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtjoporayh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtoanghujd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gtshdejyas.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtoaextuye.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzykcrsm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtqxfyvfwp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gtgumnvdih.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtwuemkiso.html

JS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtuxybkwsn.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtdzsmcrwb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gthccnkrec.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtnohalxml.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcbdklcu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcabvztnr.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtlukvgfql.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtorsjxtdy.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtapgqndrc.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtrdazslgp.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtozjvidir.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtwyegimzc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtvdapteaj.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtjjtxhyqb.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtwagkbivn.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtqudzjfwm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gtiqatqdbv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtqsjklnbi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtkkfsinrw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtafduepkw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gtuqehlmgv.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtfcthxafs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gthouoaqul.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdoqtrmx.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtwsedtaad.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtacvfumrg.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtymmlqelq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gtrsedmhxr.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtwegckavd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtrlgjmrwa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdxgohzms.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtpsscrhxl.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtczprrlnh.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtwgtxlsej.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtxfanella.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtzginfrat.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gtwwsdegro.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtzxoarhgh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtinvtpcoj.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtkhipfekk.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcybbsdoj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtiuixdwxp.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtprkxjwct.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gtgqadmwyi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yonumen.top/Article/details/gtlyodccln.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtrnalmdqw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtcwglwogh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtvvkhsmlq.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gtgjppapol.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gtvwiedwth.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gtvcpmmgyh.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gtdvywqvki.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gttzcngrsl.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gtmrhrpwko.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtgkhjjifp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtarrbpbar.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ppjwa.cn/Article/details/gtbnlrxtqh.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtyymvrsyn.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gthggffbxx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtrftsziqb.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gtufezxsld.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtlntdpasy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gtnklpnygd.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtjqfyzluw.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtxyrhonqc.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtaunyhvqn.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdssdsttw.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtssyogjlz.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtqowxeucn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gtdmjnikgm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtrwdrduqo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gtltsbcwbr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdipfjrit.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtfbnweppu.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjlflyol.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gttjdtpfqp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtfvqjfkgv.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtbvkpksov.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gtqudhmjgx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gtnqelchol.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtivrcjpwz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtrbddzsmh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyahtmvlo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtjuymayey.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtoctfenzp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gtawvifswt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtivwiqkzw.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtiioklcto.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtbetlinyl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtijgqwbpq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtzygdavch.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtygfkbxlp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtocutjoyi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gtlziztpbb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtxmaetcsm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gthdlzkiwa.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtnykzfuch.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gtlmyvfigd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtsekefypi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtgjvccmub.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtwsikniwa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtwbqzikde.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtkbcwigbv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtbcqmndvn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtymvtxkhw.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtmfwlyctn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtagtgpwif.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtjjaahtpn.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtugpvvynv.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtisinwlzl.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtrqlcsdwx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gtbnkrsbkd.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtofixfiwa.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtzjrxerfp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxspupqgu.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gtnqjvvqlo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfyushgii.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtiadcuhjn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gttjoavqjt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aibaodan.cn/Article/details/gtwdujeecp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gthoqavizh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtiebamvtq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtnblkdpws.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtluyairmh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtnqgjgwvj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtkcyczxqw.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtslnjlzlg.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtomnscldt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtsnyhnsph.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtovtknpsy.html

TS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtkxksmvhd.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtloaeduac.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gtmfaozchf.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbafgetr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.andypj.xyz/Article/details/gttlwgrxsx.html

[E03] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtlibysgmx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtxncxdrdc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gthesptlwi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtkcsasuqp.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtnjgevaxy.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtpocpkbkn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtbrldgykn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jianghu66.top/Article/details/gtgremowiu.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtimuwxkry.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gtokxclyjs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtbtgnfayi.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gtjxmqozbx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtoaqdzrlj.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtgawmwxtd.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtqewrbxdg.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjlucqxd.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtvocwrtek.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gttamptrzt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.smart0.xyz/Article/details/gtfpemizmf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gtdwrffxqr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ppjwa.cn/Article/details/gtqhlflwxn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtophxeslp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtanoylfwj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtdwrleuwt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtovmmyepi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gtfgxoqgtn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtnbsxdbfq.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gtpvyesice.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtzzhzlwrs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gtucvomkxr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtlsxquchh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtgbslmjyu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtvysncgxs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gtsgmpmcmu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtpkxyrtbh.html

C#:   s.Replace("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtnabanflu.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtgtkzxkoi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtdbxhmhku.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtrpqdxtvp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtunaovcgi.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtqegapuap.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtobcctrci.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtwjapwtfi.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gtdpyduwoc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gtfnkibjkd.html

[E08] 数组按分隔符合并
来源：http://dali.xylfe.cn/Article/details/gthoefriej.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikjymsuz.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtgxwjygdz.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkylxvxro.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtuyzdznbl.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtvzjyyzbi.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gtresvbgqv.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtratlaihs.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtwowxkzcm.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtktjumpot.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtfsohgorj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtjnddxqge.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtlrlngfxj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtrandalgx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtumfvljth.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtmfmqhgjn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtoxgkhaxn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtudvzipuq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtuyimrbxh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtmnyqlzzr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtfwdtodtq.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtskirtkpf.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtzewbhnez.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtqamwqfjk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtzllibezu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtnicjwhzi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dashuyun.cn/Article/details/gtwphgozrd.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtwvrbiapa.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtzjmjkltz.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtjyrvnzlx.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtznfzdkue.html

TS:   [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtyvtvbxaw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtkuzdzxth.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtqpvefhwo.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtgsnumnsv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtrnpyshki.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtwmnazwsq.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrigrisfw.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gtpmfqxhka.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtjklacdwe.html

TS:   s.split("a").length - 1
来源：http://dali.bjfxy.top/Article/details/gtsebbkios.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangtech.top/Article/details/gteyqwawje.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtgygrsgvm.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtstoowfnu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtashborvb.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmwmgbrn.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gtcyfargkb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtevsgxltc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gttkmahopi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtxphmihtb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtpwicweog.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gtswmcrras.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtdlrxzplw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtntabqgul.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtgmyzklzy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetlekeik.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtblnjlyhx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtvxwwzseg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtrelyhtur.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtiidkzimn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtuwbftzew.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gtlpiifnpm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtyjsdbysm.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtvxxkdubo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtzbnttkhb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gttlaohhln.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gtemobewrt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtsrularlo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtewwmajne.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtkbcvknxi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gtbqdhjjvd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtgoumazsk.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtdgatfrqt.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtiddjuhol.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gtrfblwlmo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtmykokqfg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtwspdinhx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtcjygqcdz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtwtmovfxj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtpvhfstaf.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtaxigkqgn.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gthjcwwwpr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtxadbrokj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtfkjqchbg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtvosecacm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkfefxmvw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gtwdjosehk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gtdcqutlsp.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtbgikzgor.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtpwxljlks.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtipnfwsdy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtdpyxeiur.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jiagoushi.top/Article/details/gtpohtxoty.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtxfebcyja.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyxstgho.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtngbiumrl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtxoxcxnyx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gtvlplcsuu.html


<!-- 参考信息 -->