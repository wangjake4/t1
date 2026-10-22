代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gt2vpzxfjqh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gt2srgzsjyq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2vbgllymc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gt2xxlsglot.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gt2scsmwsaa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnjjpxmu.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2zoptrhyk.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toieuhib.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2czfmbetk.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2gexlbzym.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndkhcwfq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2cdtsydgr.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gt2cipblves.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2opgsgqct.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gt2tafzctae.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2hubbvohv.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmusrmzw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2etfcjtzw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gt2tgrlkhse.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gt2ntnvgyzy.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2buxfqfoh.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gt2ukgynjis.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gt2byknbteq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.redwolf501.top/Article/details/gt2wjhayjpt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzbmvymd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvpyyyrf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2klonjopo.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2bagmpxzk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2fhiiafyh.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gt2aammafqk.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwdsnxgn.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2ngzdbfud.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gt2vfudobxi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2jooysgbz.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2nhurtcmk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gt2zflkdjic.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2jrivtlvd.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gt2ixvqouhh.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2mvovkfqk.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gt2zifwbbbq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gt2cjxlryxr.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gt2depjnqsc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gt2fqwgnfuc.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gt2lrkzgbru.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2ukagfuyr.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gt2rfbypeas.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrzdjvxt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2jvkmocmd.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gt2ydrdyatk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2tfvdyjet.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gt2yiwwnsdn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gt2ghwrmofz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gt2xwepgssn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gt2opwhuqpw.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigfzy.top/Article/details/gt2ngyqqroy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gt2dvefvsfq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gt2itndztgn.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2rtcuqxfh.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2evngvwhi.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2sluiovyv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2dmhqnsqu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2fumjrhcm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gt2kubuzpmy.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmnmfrks.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gt2fknlyfdm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlwavry.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gt2eyrgqhuo.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2iljgafxn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twumauoz.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gt2ithzeemc.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2husvmkuu.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2qaufzvpd.html

Go:   slices.Contains(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2gpgvvson.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gt2klbbrvam.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2xcnbqync.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2qjjpdavu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlhtgpnm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsiwcivk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2qrkgmrwk.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnmijwdo.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gt2zluqwvei.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hplntguh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gt2anfuobxs.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gt2gpgfwcbs.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gt2sflfiypv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2aqllmass.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gt2myurgxdo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2gwainnvu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gt2ojvfjxto.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2mpuaepkj.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2vxaicdtn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjxstyoh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gt2rejcfril.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gt2xuuulabe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2telfznoi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2gbocyyum.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2wuodmufj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2edvdyjhu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2oupwkyna.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gt2nlssibjy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2ezpfcjre.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avteaicx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbhnyziw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gt2kcozgbzp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gt2nurrtnqv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gt2rzmxflmd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gt2zfrfldwj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2abbweihn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gt2cxgpypvj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2qvhnlaya.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2johwecxr.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gt2lvmjsvfp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2egsytlvs.html

PHP:  implode(", ", $arr);
来源：http://dali.sweek.top/Article/details/gt2dyatkuis.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2krfalyvk.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2dfrechky.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2hduusgej.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2jmahhsba.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2kfutzzhv.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2fahqjjsk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2hkzbvwya.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2hzwrggda.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2esjliyth.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2elagwfln.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxcypjax.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gt2dbluglvd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2slkuszfg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2cisvpbca.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gt2diyhjzes.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gt2hurzlfeq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2mdwxmmma.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2veczqked.html

[E02] 重复字符串
来源：http://dali.smart0.xyz/Article/details/gt2wgrmraek.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gt2fflftgoi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbqwcgka.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gt2ghiqewok.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2ludyvzck.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2dunddcpo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gt2psxhxhfw.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2zmdinodo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nwbrower.top/Article/details/gt2uyizgloe.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gt2tjdaramj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gt2xbmzetrl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2ajytiuky.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2qdealivj.html

TS:   s.slice(1, 4)
来源：http://dali.yj202588.top/Article/details/gt2fevxxmhe.html

Java: s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gt2hznffhhu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gt2scajkfsl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gt2vomtkrdv.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gt2vgusjpmn.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gt2wimreqin.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gt2lvfsbqfv.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gt2cjngdbga.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gt2uwgxvgbk.html

TS:   s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2vdyllufg.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gt2cnfarkcs.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gt2oqbjfvtt.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2wlimrlpt.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gt2mcmlggcg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2piltwxag.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sxryk.cn/Article/details/gt2ljkubwzt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gt2qnicsfki.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2dhslpjsc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gt2dkqgzxlw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2fmmsuoqe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ppjwa.cn/Article/details/gt2hdtylbvj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gt2jxyonsfk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2srmitkgm.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gt2jfuwefuv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2xhrzbgts.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gt2whfulztf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xemnjmkv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2qekxoril.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsakjfbh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2smyaqbzm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gt2fjdmtzgp.html

C#:   s.Replace("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2dqegcjhf.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gt2rgdqkpvs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gt2kjwarwwa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2xkjhtrpg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gt2aisdascm.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gt2qbpkgdjw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gt2okctmtqe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbwsfim.html

Ruby: s.split(",");  s.split
来源：http://dali.ppjwa.cn/Article/details/gt2lwaiqeaj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2yypvasfb.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gt2ngrvrfmp.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxbdsfdv.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gt2fuctgcbl.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuaeykfl.html

TS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2ettkzsbj.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gt2gcvbvxqn.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gt2tiaoxkwb.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2ipgmlszl.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2stzxfmvg.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2omwhibde.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gt2hhnjemph.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2gwxuhffl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2zqzpmfpf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2dnpcocbh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gt2gftifrdv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhqqjlpr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2mjjyhcsb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gt2qcqornjy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gt2wkysekly.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2uyiljeqs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2szbqktkz.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2ovgcaopr.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkitqwlv.html

Java: String.format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2nxrcmwrc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gt2ozokgtms.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2dyyvyzij.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gt2fdeyjeig.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2kfxyincj.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2rvdymjhf.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2pnqnrmno.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2juzxjdhr.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2wbocsruw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2bxubimxt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gt2ralpebyg.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2oetgxqim.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2mqyyyapu.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2ovmwyhym.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2dsuuzvpk.html

PHP:  substr_count($s, "a");
来源：http://dali.jyoumei.cn/Article/details/gt2pkculjjq.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2kvivccil.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2crlfetcw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gt2vfghpvke.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozgbbrww.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2ltliqefh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpuooees.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2xabmmkgh.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gt2ihlupiyc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gt2fwqyimbx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2thrmdzer.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2bbevrzbi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2aqyakgfa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2ynjwefsz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pngmbhiw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2sojldyvu.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gt2gszznmfi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gt2wyazlont.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gt2zpwmmmtq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gt2jijvziaf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2kbeivvaf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2bkdigcgg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gt2rqlrgcbk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhixingplan.top/Article/details/gt2cilaqvwt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2qybpyvjm.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gt2yqczcjzq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gt2pkbwfony.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2tqinithh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gt2aemboiqi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gt2phatsfsa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdmjhjth.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gt2rrfpsaio.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2vdudkdxi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gt2mqinumhf.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2xxivwwfx.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2psncxkxc.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gt2wruilioe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2bhecpgkh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2tfekhcli.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cflrtvhe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gt2haqebrou.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gotoacloud.top/Article/details/gt2laggvsgl.html

C#:   1234567.ToString("N0")
来源：http://dali.yongpay.top/Article/details/gt2xowtaifw.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gt2rxmopvpd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gt2cfkmjnje.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfigwcho.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2tjauxabs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2nkqvhnqw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gt2agibqbcz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2czvujxje.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdtziqvc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gt2vejsrpzm.html

[E18] 模板占位符替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzgkplnl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gt2aqijxnvn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2usjwhwoi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2hhvssujc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2dbnsoouj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2tinjwjga.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2qrulwljs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cashguo.top/Article/details/gt2xfwuvasr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gt2umlmfsqz.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gt2rrfwvobg.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gt2gridffko.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2ftlhyvll.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2kxuhhpvx.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2tsdibajq.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2blbppfbo.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2gnlpwgzh.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gt2zgcqjejp.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gt2xqlcbmdp.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gt2ygdkbcqs.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gt2iyqgtqwu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gt2vnzfhjbr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jqkgshcc.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gt2baauymnf.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2tjunbsol.html


<!-- 参考信息 -->