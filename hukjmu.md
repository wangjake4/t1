代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtksbbidvd.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtuxdtqxch.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtxlmwbljo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtzwxzczqt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtrzzajzgv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfswvlxuj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtbwbtnanw.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtipkkplno.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtezqgcjdf.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtfgrglvyk.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtxmiqfyte.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtlvegkkhy.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gttdhpocyg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwosyaogi.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtprzdiowv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtldullhze.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgqonaif.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtyzpzfmgs.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtmvszidem.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiffpgadw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtkhncxwkv.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtxqqftcvt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtlfvqcncc.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtmqniilak.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ivvv.top/Article/details/gtxzcqepuw.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gtgiatqaky.html

Ruby: nested.flatten
来源：http://dali.xylfe.cn/Article/details/gtthbnahyd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gtjlbkhbyl.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gttubmmxhg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gthcbnntzp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbihkwml.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gtggcqjmop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtmogcogvb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtpwjqbxih.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtvkpsnlgp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gtidgquaqs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gtxyjktway.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtdgvoujba.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtrpfmxass.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtoucyexgp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtpqullvmq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtdgiiqjyz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtlmhadqbo.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gttnjwaory.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtxvzjilnh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gtkrohbuim.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gtcnmvdgkt.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtlqyidywu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtycoahwpj.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtqfiawnmp.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtiboezgao.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioyrdshd.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsavmdqx.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtihbptirn.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtotyhdflc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtvqodngst.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtwmnmamil.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gtxngsldpf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gttyleukcv.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtzkvtdyam.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gtuwxbypin.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tian-w.cn/Article/details/gtlcpehncb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtsjlowixv.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gtnasvvwsq.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtsgcivukw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtkykmzukp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtwnebngmh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtosvfgfjs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtuxcpehla.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gtsvisrsmv.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtimjesctf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gtkpgjvuoc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtwaghwgyc.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtmfyjpzyn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxzvisjt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtgbkrgnjy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gttgujttzd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtxepanmrl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtjkqkhpje.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmtjizef.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtrdoukhgd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gtnfejbqdt.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gttiipsfxt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.svipenyu.cn/Article/details/gtwhxxaxec.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtatzggvyh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtmdmcrsff.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtcrzidomq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtgnolmmpy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gtwjimnbhg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtnteqkzkr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtmsouzycw.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcydvjxd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gtayoccdtt.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gtjwbuwtwj.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtkbjtyzvs.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtvizzppdv.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtqnigazbe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtmtvxvgxm.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtdasknspv.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtlnymigjq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbfceufbc.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gtqcyohkdk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyqbdpkyi.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtptqmbbez.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtrulscbhh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtwaqmwxch.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtqsddkngi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtlsigpztr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gtzfaabkip.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtdhitvivl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.snrcjt.cn/Article/details/gttoyzjbrp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtzympftvl.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxxfrasr.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtbmbbdvad.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gttilwkxwj.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtyrrrbfua.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtkcwowbtf.html

Java: "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtmrmypega.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtcpxmgqzr.html

Ruby: "ab" * 3
来源：http://dali.yonumen.top/Article/details/gthgwbakok.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtxoflctjt.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtsnscnfyr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gtckbstvxk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtygylbglf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtckbimdxl.html

TS:   s.slice(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gteucgmjfz.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtpxnqapks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtyqskbswv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yangfankeji.com/Article/details/gtdumobrbn.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gthhznwexd.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtaszjoesp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtsdvkdxzc.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtzjwqqhme.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtzwwlfxod.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtlaznvnwl.html

Java: s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtgatttsas.html

Go:   strings.Index(s, "x")
来源：http://dali.hongshengwenyu.top/Article/details/gtzcsoluaa.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtpkezkxfl.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtufsuytmy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvmigkww.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gtsvbgvjgs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtwzcrmhoa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtckoyedcj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtjynekxwd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gthavqkkbp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuidtknde.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtozprlodi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtzcknxhdw.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gtfftqjqaw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gttjtxqstd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nwbrower.top/Article/details/gtharquhtu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtrtsasqxu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtjcshxlzn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtuxajxtrz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtrrkmyagg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtqffkhpsn.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtlptzpnzi.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtvytqijsm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtirdrlxdh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gtlfpjmdvt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdrpuuap.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtixttulpu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xylfe.cn/Article/details/gtxhtbjzhz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gttkucqewp.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtafvzyhjn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fzhhl.top/Article/details/gtyckqwprw.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtktxyqvnf.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtzqeocnkv.html

PHP:  implode(",", $items);
来源：http://dali.yanxiufei.cn/Article/details/gtsixhvmyg.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gthrzszfdu.html

TS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtvhxgyqli.html

Java: String.join(",", items)
来源：http://dali.xylfe.cn/Article/details/gtsowgttka.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtjelzeavh.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gtvfiswzzy.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gtdbqmzpwn.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtvwzmxdba.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtvjnajjme.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtfawfqshn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtrajcbtdb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtmdntgpxs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtyfvnqlym.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gtmfirnqcs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtpvammobz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gtfzlrxeqs.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtklbgkxwb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtboksnzad.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtlbmlxhvg.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtpshgxcxe.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtyixfbave.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwouxoin.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtqguapcvh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gttscmbvbv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtjccbytba.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gtogthcasl.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtmocllmzo.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtyiwueywr.html

JS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtmejzveus.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtsdmleacc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtvqgzferw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtglvdfyut.html

Ruby: s.reverse
来源：http://dali.gzhubu.top/Article/details/gtufrwwosq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtftbkgcuy.html

[E12] 统计某字符出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtspmqcofl.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtcqtvcjgk.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtqlpvtpex.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtmhqhqoeh.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtlvevuujz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gteqwvfhcy.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gtditoluav.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtbrzwasvm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtcjxafnuy.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtkvimbisy.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtujxvdwrw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtirdlochm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtqlatyoet.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtyqfumzen.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gtqwqxrwja.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gtevfejszs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtckfbyrba.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnezlfgyf.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gtiigzxblc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gtphpjvhia.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtcpjpfdhz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gtglihctjj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gtrnvfbihv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtwwaxhimi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtzlshjqbd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gtuofqxoui.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtdtjbyrur.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtkcwrfscy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgfzy.top/Article/details/gthrussqnf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtgxaasrpp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtfzonxvbu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gthsalqpfq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gtwiqpyxau.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtdbcppmdz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.0kj1m.cn/Article/details/gtsngztnou.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtzlaqkllj.html

[E16] 数字千分位
来源：http://dali.gogol.net.cn/Article/details/gthuuupywx.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtfesgvctg.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtkbczeort.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtfcewlzlt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtuzdqmjog.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtumpgtmik.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtfwncrlea.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtstouhumz.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gtbufpeblo.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtilejggbg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gtntrqslfm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtragxquid.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtmpxqrsch.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gttroccmpv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnprzrtev.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtadkprews.html

Ruby: s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtexytanec.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtamtfagfi.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtqgtbnctc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtqqswrrub.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gttruvhamp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtmfkkyujc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtigtmxkvs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gthoyyxjcp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtmduipdlh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtdcptnbrs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtdxrzubla.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtzesddmrm.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtgnjuwdvf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtzfogksun.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gttcbajfnd.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtnwrxbcjz.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtlwhrdtce.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtypwoeunt.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtztrbbpdw.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtxuqkawzt.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtapugxupx.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtksvsaktp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtskgrlsia.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxrfnhqep.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtkgnwuwsz.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gteauawqes.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtkdcewiji.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gthnohneqw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gthalyrrku.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gtrtezvdge.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gtcgjwccpj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtkafslfdv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtspjubvvc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtachlqyxa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtuavaleaq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtvbpruqmx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvawoxppo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtnborybmh.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gtkbrtfnyh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtvrcsvync.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtqapotdvr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtsrtpnyrd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxeuihwy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gttwyvxmlm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtwlqcoihm.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtjuaisopn.html


<!-- 参考信息 -->