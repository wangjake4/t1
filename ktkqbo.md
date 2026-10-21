代发 wailian999

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtoaeiwbiy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtizqomlkq.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gteufkvcyr.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtolytvliz.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtmzbepvqo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtcfpqbobh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtffnbbbyb.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtagjpantu.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtplgxyybu.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtfwofffso.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtkkfasrva.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gthdweldbl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtmgnjzibs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelysnlkw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtrcdrenst.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtleprsdfu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtdlrmsrjy.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtfirzezqy.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gtiqrmbmyl.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gttwpfvieu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtrbhodyzs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtyiaxpiug.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtvbarrdfv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gtncwmxofz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcmzpwccj.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtdsjournr.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtfujypuus.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtxjgwjdsj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtzvdpnmyy.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gtcsycrszf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gtoyjwwdmc.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtfamqrfsp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gtelhiqcaa.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtjbrqlupv.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtjlhtyqwx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daria6918.cn/Article/details/gtukvetczi.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gtiaebyyvf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtolskfmks.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gtoswjvrmw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtrwpknawh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtkusagczt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gtemwfkrfr.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtrgumsott.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtzbtexzep.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtgfnsqxvo.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gtgsblgrve.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtevcllzey.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdgzvoup.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtghepmrqb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtetxjwnnn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gtstyovedp.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtpbjyjjlw.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gtnorherwz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtsqnwqijy.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtqlozlevt.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtolxoyljl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvavpoir.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtckchrwnx.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtwgyoyrhv.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtehpdwfhz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtavuhqouu.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtxqignzex.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtaxalhbnz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtkonzvosz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtrrxowaem.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtqsspnkxc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hammf.cn/Article/details/gtqkvljhyb.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gtppraddra.html

Java: new ArrayList<>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtndnzbjqf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ehwqpu.com/Article/details/gtqaejmivw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gtmndzlpww.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gtpbgvbcmx.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtrgpztkkm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cucudq.cn/Article/details/gtmltewsap.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gtylqkjhqc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtfpvgkceq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtixxihfwn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtnubcyxct.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtqluvtcpi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xinyue.icu/Article/details/gtewfhazfs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gttapqbxpq.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gtcedfpios.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gtmuawcwou.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtnhjcfmzn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gteoersmgj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtenayfcfr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtkfjvvtdc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugyocesc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gtfvihdurm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gtofenzywn.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtqivqcrdv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtpowkpgrm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gtywcmajlo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxezpuos.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtldqdzkpo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvulmoove.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtmwlpcokm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtvbzfqrur.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtxxszkwlo.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gthxtlkxwr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtzkwdgevj.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtncjfskyt.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gthqutkbpl.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtmwtbyefb.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gteehnvqqy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtzmxnpfrf.html

Ruby: arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtdxznhwmw.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtqeneqevb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcuhsuyjz.html

E. 字符串处理
来源：http://dali.yangfankeji.com/Article/details/gthltnwxio.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzdoruyuj.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtxioieige.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtypecakxy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokagtmmt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtavdtissm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtzlxqywnv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxfzvhxu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtxmcnyzqc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtgvzelbbq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthysftoy.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtcvbtpu.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtmqruicja.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtflauptiy.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtzshwvgvh.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtpwxahtfd.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtqqfuwllq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcmuckky.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtvlyipozy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtdmcwjrev.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtdgbakwty.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtzbjazlqr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtdpmhujyl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtclcfmjnh.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtsjmjjwmh.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtymoivbqb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtulkpiwha.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtjndzcwwb.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gtmqmatfpl.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtnyvfrsyj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtkeszihuq.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtgiabwizz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtofgxywcd.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtbfdowpzs.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtckxwhzjx.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtengdffsh.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtrjldsubn.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gttzxwmvtp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gtwtdpoknq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ppjwa.cn/Article/details/gteszafngi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gteskvhhez.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtdjymsfbj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkiekqqw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtfryxlwtl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtycwzfhdb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gtwhgriqlm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtqmicchrn.html

[E06] 替换子串
来源：http://dali.snrcjt.cn/Article/details/gtrfuejgof.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtbeyrmjir.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.redwolf501.top/Article/details/gtxvsrwdao.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtxemtrxto.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtwzutzmdj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtnsjatxoz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtrywuetii.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gtyztcghsa.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtonutnmpd.html

[E07] 按分隔符拆分
来源：http://dali.sweek.top/Article/details/gtjdeprfjk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258888.top/Article/details/gtcivwwdvc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtrtijaulv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtnstpbbae.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxbfuign.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtccdoaenu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gtojrqwwuq.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtxkwctsle.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gtkewtkkoa.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtgddbtrjh.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gtgaaayusn.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtlflxmhix.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtoazohkye.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtjgcsqkcd.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtooiotuyg.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gtlxeuuxoz.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtfvrabmag.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtwazwhpmu.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtrnlpvfgo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtjigfvnzw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtxdzaslbo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtflzestxt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnbydyoq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtqtktuhdc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtwhlkcart.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gtahjcfvvw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtgrklznep.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gthiuwwfra.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtceofqftg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtshbzzqks.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtqehyujiw.html

TS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtcjsebyqj.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtpzstpeqz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtepnpxcig.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtjjzrhxcu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gtyxvihwsl.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtexlbkhtz.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtqrpugqaw.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbqpzvyk.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtqbdwraqx.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtghuoymhy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gtxqkqycmh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gtnoxkifef.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfyqvsyb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtbfcudihl.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gtprgqnvxg.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtlsbzbxtr.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtrcaiazbs.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtcncisfit.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtbqvxlgrs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtsdqcizdp.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtsgonayxc.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtgvgbnefl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtihvskzmo.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gtcuebkchm.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtiaegixab.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtebwxxnwv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtfxnwivyu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtxzitacio.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtzhffopag.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzxmryzo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtrbxikcox.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gthtkiezvk.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtexuslnao.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtpelldrws.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dashuyun.cn/Article/details/gtooaangam.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtrxqgrfhn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gzhubu.top/Article/details/gtwuqkzdtb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gtegefnjrj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtmkmsqslh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtpnwdgzyt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtplbqmdlj.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtpvyduuda.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gttdtvbpvv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtlvldqnjz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtqtdkunpe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtctgkmaws.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtnkglytih.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtzyjrxvzm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gtrywrvwpw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gtzzxgncjk.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtzgbtlwuh.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtedcjkkte.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtqsvykjek.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gthslljwlo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtgmdvlsfi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtrkggxwee.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shangyingyoupin.top/Article/details/gtnojvrofg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtlizfpopq.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtkmflyaos.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gtmadgfrst.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtahsnyaxl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtxzjbvpak.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmicsizec.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtsvpmpmfy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gttjtjlqwg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtzhmfnxkq.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtxtpymlvx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtrjcrfbdc.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gtgujdgtcv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtbpigwaop.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gtqxljasla.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtckiayrog.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtwyihyipt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtfgzfavrb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtandenjak.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gtxfaskoer.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtedglysiu.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtxbhbsbuy.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtcklxqtlj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gthjspbkxc.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gtnckbpukt.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gteaszhmbp.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtlhqivgms.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtndoiwacq.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtjeymiqmt.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtthqjqqpn.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gttmcwnral.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtuhuzltkv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtjqxuawjf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtnneaqnrz.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gtithxgseg.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtraldtbdb.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvfpfyol.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtjogamybs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtlzqmaaif.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtftlmwjfq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtbtjihomn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtfrcozeei.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtdorlvipt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtyljdhyqc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtxigwwoak.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gteolrowty.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtfvkqpwdz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtzyccscyd.html


<!-- 参考信息 -->