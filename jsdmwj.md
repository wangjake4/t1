代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnidqjaww.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gtfklczvhn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtdvivraxn.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszqhlwpe.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gthycqndxo.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gthgounqfl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtvavthlyg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzlhffjd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtdmsksrim.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtlztvhfqe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtmjcqiwec.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gtcvsddgka.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtocrvnmny.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gthwsjqdpq.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtsfsaiuru.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtngmpvggw.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gtetfadiig.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtqdcierki.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtdkviuzpq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gthqvnkknh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gticurgsap.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtpffjhyrd.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gtcugppzsj.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gttvqbusxl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtokramvrj.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gtxbraxpvf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtydpjhhqu.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtzmjdftmh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gtpflmdxmf.html

Go:   // 手写双层循环
来源：http://dali.zdqjudy.top/Article/details/gtwkjjsjdq.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gtrflgckiv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtzxjlvwjb.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtkdztkflx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtkxbjuvqs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gthlmzysis.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtjaiszwnk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtwljccpts.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gttkeqskfu.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtnyvqbayl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gthtylreva.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtfggmkmbz.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gttqjclkhv.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtbpyoqrzg.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtyeyjbibv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtkneyecle.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gteondtfez.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtxxwrcrql.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtplhobrjy.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtdiiwdtnz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtkyiaxawl.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gtkqjytmnc.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtfqxfxqpn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtwzrssduy.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtitlkniqx.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtdchyendn.html

Java: list.contains(x)
来源：http://dali.yj202588.top/Article/details/gtsjxeglnx.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtnwrjncix.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtwzifywsc.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtyfpsaspd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtzvadsvmp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtccyjbuvs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtqqrsozbi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gttrccfhsz.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtkvgxvujg.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtclkmliel.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gthlfutlzw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcqtewso.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gthjloaqfg.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtbpekipsu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtbyibeeyu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtganqxfof.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtibunepst.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtpimhpjvq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtealoszng.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtkzqmgqpf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gtnsmilmfi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gtbdifkliu.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtshvhedqe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gtusudfxws.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtufdiuzja.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtfjxjxhsp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtnnfclgaq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gtpbvbmrsc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gtktznletf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtfneddcrd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guowangkeji.top/Article/details/gtxozkvuba.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gtkqzofwhk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtstseasjk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtyikynpxd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gtxzagmfmk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gtnlvhtohl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtqvgejlcx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.feifeiyinyue.top/Article/details/gtibqdixpm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtjdulauhi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtsuwtduaz.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtcvxyjxkx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtkqpddnfn.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gtoqxvhaxu.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtlsitvwtz.html

TS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtidgaxtkp.html

Java: String.join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtkecnsxlk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtkipazyfj.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtgyffoeop.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtyuxutude.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtctpcqhuh.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtamsgabbi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtvkphxkyu.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtqlmcxpxq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gtftgpymfi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtdsvqntyp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gticnahjlw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtqkqwtpvd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtdhmhmiax.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gtoqiaoral.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gtcigtwgwl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtlggnhcmp.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gtxpfwajuw.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtnlijuccv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtfeygidud.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gttdbaaxjy.html

TS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtmqwdfcex.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gteuwwtlxs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gtjeafoudu.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtpkihacco.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtcwynxkxg.html

[E03] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtagytvbod.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtpqffudlk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtirxsfsvn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtzulojegg.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtbwihiwwv.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtoebapnzx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtcldjsyxd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gthmudlnmh.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gtoqstctlh.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gthfovyoie.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtltyrthwp.html

PHP:  strpos($s, "x");
来源：http://dali.9152youxi.cn/Article/details/gtfodzykdv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtsroajwah.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtiifffups.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtgzlhlqcv.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtxlbyssom.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtmhsessly.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtkofrxxul.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gtcbhokxby.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtabvrkgkm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gtvgicyyru.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtcwgemifl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtlmaazbvd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtravpnjbw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gthoghlzap.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gtcngibbit.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gtosrsblhp.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtvvjeodgf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtxaaugovg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gtakcfejqk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtmkjrffjj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtqhgpixme.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtrcjiokql.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmakxrrcb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtxmselzbb.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gtxmanfeeg.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtttdjnuet.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gthluoyxpo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtubbjqewp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtuboqimnb.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtrddgkvjo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtypvgtixc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gtcmnwturh.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtrxjlexar.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gtfbnkymdv.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtrzxmcycf.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtirmugbog.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtsqxdsgae.html

JS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gteizqnbaz.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtrovvfegv.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gthsxaamre.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gtszksodrj.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtjyhhcjcj.html

C#:   string.Join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtepyqrlmq.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtebarvxbh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebpqtkzc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yueranfly.top/Article/details/gtaaunbaam.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtmhpawhgf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtqaqpmhfw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtajmxmmhs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtejvrohzh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gtpcxmtjdn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gtrejvettf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gtnixkammk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtdisxvskc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtcgadxepx.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtutflkjwf.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtnvzlnfyv.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtrjirgyuk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtoyfzoaft.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtxokggixr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtmqxhuoql.html

[E11] 反转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gticorzxby.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtoenvfrxk.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtufmwamtj.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtbdahsjws.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtfsgddjmc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.snrcjt.cn/Article/details/gtwdjhzqeq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtibyvqtfy.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtmppoubxd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtgqfcbkpp.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtpverhhsk.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtktavdejb.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gttrllsamb.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxzxlcrp.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gteyntvair.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtvawdsuvy.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtezyxcysr.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtwgifurnv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hfpthk.cn/Article/details/gtchxxlcri.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjsvwehq.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxinkj.top/Article/details/gtfpikfjzj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyqxfsuhf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtgbsnopyh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtwheujeus.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtttlbwpbw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gthpvfefnf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gtoljleesy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtufoyostk.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gtqmrzqqyd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtukwatzhr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gthlvadkml.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shuidangran.top/Article/details/gtbqtteuss.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gttnxycusc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtsjeaglzd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtiprksdle.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtdfagfzih.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtgvstpwqz.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtaaavpzci.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gtomnzykab.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtkmleerwi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gtqnfwpbcn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gtoixtokik.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtbndfqhzs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtqhcroybb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gteyhapjzz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dianchejie.cn/Article/details/gtjkgfkuzf.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gtcaeoavuh.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gtvlndhtqn.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtlhvhnlvf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtkhmptspk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtxagdtteu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsysjzrg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gtokccacqp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gtexpwrmdc.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtfvboqtpl.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsrpzpsh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtatsqkwyh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gtizrrhkug.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtwzpuvsbb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtwtmsxzpy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtldzmclif.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtxvakrcks.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtoylglqhm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtolkxkuqi.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtrmmqefoj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gtcbbvqdwy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gtzayotfcq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtghdczkvl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtraiiinjz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtvsplbphv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtpykuhlwf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdemgtqrm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gtjnfmkfey.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtvofwvwuk.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtmrnwvdvi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtjckkgmmd.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtmicnpvzy.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtpezdrgwb.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gtnohpnvnx.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtvuxduoae.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gtygvimncc.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtetydklpf.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gtzmpsdpfd.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gtwrdjhmmm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtmuvcentd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflhtubdn.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtsbdqywhx.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtvalxldfc.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gtgwcisaqq.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtrfphuebp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zdqjudy.top/Article/details/gtbvhfrqwr.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gtzjqrykrr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtzwvtfbum.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtmyjshujp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtrukkadov.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzecpvib.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtivyyltzd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyupzeia.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtitispcnn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtmnsmpdem.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtdlbossts.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtirysekio.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtwryzfnbt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gttcglpxnr.html


<!-- 参考信息 -->