代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtvusmnvub.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtuzwdapgl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtkstohhqo.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtgzrzquju.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtbcvndvdr.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtqgsxusnv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtctjeorjx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtxstbrziq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtmkdgartl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtcqcdcyrh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtvqhocfnc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtneohuxcx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gtyxzwrwlx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtqsebpjde.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gttgbtpvjv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtlumrbqon.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtwqrtpkeu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtfpwdfpih.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtdqsbhwib.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtedjbvm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gtvzwtpxoh.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtxyhkvpvz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtusbwggbi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtedohncib.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtyvyavall.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtzlyesobw.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gtnyqkailp.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gttqobdywa.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gttkbpfifd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gtmczjkpis.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtkkxjgace.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtpnvoyhab.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtpglhbato.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gthyugnkaw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtiqhrgvil.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtwsppxgqz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdjhzrdud.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtzsgecgah.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtskfkocju.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gtkkiicvgy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtartphkab.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gtklemosam.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gticumytls.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gtjyzfeuau.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gtimjnuscb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gtypdgvkem.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gthfehpugc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtybkiivkd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtohuttlxl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtgxgfelfe.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtynsaokgi.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtwjepgfzv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtzsxzpeke.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtetbnpthk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtkjkmzkaf.html

TS:   nested.flat();
来源：http://dali.havefunace.top/Article/details/gtjmgtnomo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gterurcoxo.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtpwgfqpsh.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gthwbswkiw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gtehxgxoby.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtkyaxfecq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gtqoqhfmdo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtmztgzdww.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmqwnnny.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtenarytgs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtleiqzwiz.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtjbbgnyep.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gthtmgfmov.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gtllpxrjnx.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtejpggnap.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjbnaofi.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtdwyntofn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtfhvjuvev.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtuxtyuzrk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtruebbbmx.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtwurnruxf.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtcajpylhv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtiieogwsm.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfxlsdnl.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtgugmtpez.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtmpqswxps.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gthwrqffem.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtazjqudzc.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtiywvdrtr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtzjjwsknq.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtvjqnneti.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtjjwxcmwx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gtlzmvjzbw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtnmeavuba.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gtkfsutfdb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gtjbpijkaw.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtvtcchojn.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gthiiadlsc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtknxbywec.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtsnkczkpe.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtejcujcll.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnfhrktk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwvvwpmk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gtzjoygalf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gttgvgrjhy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhwarxmy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtjiasiwmw.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtpzylhdbz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtskzyiywh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtwhmhkycx.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtpzkttesj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gtxndwounx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtejspnkiq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gttvuhtwqv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtzrqngbce.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtmmubdytw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtlmneppsz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtloulizgz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtrhmwfffz.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtcrruwvuq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtelwklfgm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtqzsjtuov.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqlvzpfii.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gttmuvfdyz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gtqsatcnnu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjxyluph.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtoujfobxc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtyfydiohp.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtcfnqjepy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtqymllgdg.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtmdrnmwsu.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtmywccdry.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtuirwcaio.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtsslboeje.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtgoluwoke.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtnbaiokfx.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gteexxbxqp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzsqwyfik.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtnxukwfke.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdrwsaxdn.html

[E01] 拼接字符串
来源：http://dali.tanke756.top/Article/details/gtlkxmlxyq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtytztcxxc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtdjcpkwty.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtmynczfgw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtvlomhcqx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gtdhugihmy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shuidangran.top/Article/details/gtdgexluhp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtnngpybpx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtsgigdeau.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gthrqwodsw.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gtbauusjmv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gtjweavzsf.html

JS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtyhqgbdzh.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtfcrjpeoq.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtoyigautj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtpcccdxwv.html

Ruby: "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtkwoshuwi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zdqjudy.top/Article/details/gtkgjdnpmu.html

[E03] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtttqixjgb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtsgmqapyy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gthcdikkwh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gthghnevam.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtiwkfbxxo.html

Java: s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtqginjdwf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gttwxjstuy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xziqi.cn/Article/details/gtpatblemu.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtimwlffvo.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gtqobvcmlr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtdqwjbkmu.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtpwofymif.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ivvv.top/Article/details/gtmwpbmvpm.html

TS:   s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtmpmfazxb.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtaidlzckh.html

Go:   strings.Index(s, "x")
来源：http://dali.yuanzhike.top/Article/details/gtqjzalymx.html

Ruby: s.index("x")
来源：http://dali.sweek.top/Article/details/gtfnsigegd.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtkfkdwvgq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtuovhawix.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gttzkkohos.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gtvftgjgdh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gteugvjgva.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtnxdinnrm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtczjfbuim.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuanzhike.top/Article/details/gtduzbqzvy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gtchtcxbrp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtgidhtapv.html

[E06] 替换子串
来源：http://dali.ydzc1.top/Article/details/gteusiwigp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtseqzycud.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtlzbsiaub.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gthpjlqrbl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtzhjfuder.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtexjmrvzm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtdtlgkcyf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gttkvearvn.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtxqxirmij.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gtvsuacgke.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gtxoswhppj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtqwrpczmx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gtitzzlzgt.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gttmngqhhe.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nwbrower.top/Article/details/gtqdsuigin.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtidsouhyf.html

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gtfguaepnc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqaeprsk.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gtvxoztygd.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gtegitrhqq.html

PHP:  implode(",", $items);
来源：http://dali.jianghu66.top/Article/details/gteagdgxlw.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtvipzjlsj.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtpztysxmn.html

Java: String.join(",", items)
来源：http://dali.chenjidiqi.icu/Article/details/gtjclalzcu.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gtrpgpyuni.html

Ruby: items.join(",")
来源：http://dali.andypj.xyz/Article/details/gttpuqswkk.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtbwaijson.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtegyxtuhw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtxwxbvnrj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtidllwqhi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtjvrmqtwj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtprzaqfxt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gtoupysfdn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtddofrxbj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xziqi.cn/Article/details/gtopmrdnis.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gtzobqgkhs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtfzhxyyrg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtlwyaclka.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtvbnxyhot.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtevmxgxzo.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtgkwqmfhk.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gteplomycn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtimbqvjan.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtkpqhadip.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtykskplqp.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtwwpytxid.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtkfajgivt.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtokwghcgs.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtvqxzpunp.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtzsuiaqyd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtkfpkenxx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtubfqfxao.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtoinpjxtv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtvyjvjhtb.html

[E12] 统计某字符出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtisftvzfl.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gtatxxqtth.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtpwrgbssj.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtuojkysdb.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtuxtcbivv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtudkdgmfg.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gtnhbmrzlw.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtcfgjczow.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gtvwwpsboe.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtgcnuoimm.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtulbfrslf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtetytnktn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtjkkeqipd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gtscnzqnen.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gthojjxzds.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gtjkgpxccb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtxnvrxbvo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtqygfmkhk.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gtwssxkxpu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hongshengwenyu.top/Article/details/gthauprwrp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gtuuztmatn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtjbcamuos.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpfgzded.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtprcwobev.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtbinpxhhm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtuituphxo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtaffcffrk.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtrzmasbpy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtszasvfgj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gthwmabwtz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtzgeorzzv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtzyvntlan.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtlcosjivg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtmbgqgruu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtdmtgknrl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gtwbxcwnwk.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gttejotlxf.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtcojxbtbr.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gtdvbacvrm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcwftowz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtnhqtcltr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gtwqxhuhgg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gtekskpbdp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtksiycivh.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gtscakofpx.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtvcbrdiun.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtihelmkxi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtmpmhkvjl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtklsjzabh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgdmdyyq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtmhvrhhbz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtnpjicnfi.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtoxqbvkey.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gttuhrgotl.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtzyfxsttd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtctlzkzdk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtbgvbuorx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtzkfvkagu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtxgzodbeh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtalewugdk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtcekvsweh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtddtcgaci.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtkwndehvg.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gtiernocgo.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gttreyeaja.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gtrkqgghlh.html


<!-- 参考信息 -->