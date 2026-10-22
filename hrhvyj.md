代发 wailian999

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gtsjxvaobk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtdlbhxhed.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gtfzooldix.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtvqftuetd.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtuskvistp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtkeyxtegc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtylgvtjop.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtgmmlcfhu.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtlimqcezg.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtfsbirkxl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtujfchhaz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsebbogd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtvemzegnz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvieymoe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwjpkjad.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtjghxomae.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gtigvexffy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtonfqlrhv.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtrpdxlrut.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtufywzvbb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtcrotaclm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtmitsmbuk.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gthdveiyzx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gtrolhxkir.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtuftrfnph.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtfxxjkukp.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtsrhsydlf.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtceecexvw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtygemythn.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gthkdcjlli.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gaohongyu789.top/Article/details/gtboeajdak.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtfkgoavze.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gtchquztof.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gthofwhbsu.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwjxnvkj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gttbqvbfav.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtibaddhlk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtyvhhlozs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gtarddcjhl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtsflluhxq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpqmjxre.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gtetthskxh.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtbemvqkrp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtleogtlng.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtdihdvzff.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtvzvfcfod.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtanfbwgjs.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtaqxeqkpy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtldosadvb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtdohzfvxv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gtjxldveyd.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtflefgqhw.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gtdkhllmhq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtagkeoihr.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gthvtjnlia.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtygcyerit.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtigymvgva.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgkemjfe.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtlfexgwgx.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajwpqgbc.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtdxrfpczk.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gttalwiptj.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtccrrkdfh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtlljkwobj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtdqhzeqmn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtwgvojuyu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtaihzpcua.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gthgiztazq.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtkmlydncl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xinyue.icu/Article/details/gtmiqkiihi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoamyoome.html

C#:   new List<int>(list);
来源：http://dali.cheryme.top/Article/details/gtrnvspxea.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtvfvgytjq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtfhrkwwpc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtuxzdtjvy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtqytwbbyd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtzjvdnzzu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtgapflkbm.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtrcahnapz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gtvonsmsdj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gtrmnnetia.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtkpzwahlj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtlzvtuzyc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtmznwhxdr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtikqayboa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtfrvscybh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gtgfqffrba.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtjzywrrlw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtmyzbukzp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gthnlumntj.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtgzaquume.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gtpgdcldec.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtkgltfhht.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtiinfkeyb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtpsqlaeii.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xinyue.icu/Article/details/gtmntptreb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtkchlmeud.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gtfkbahqxs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtmdhewmnt.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtlnjwrpeb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtyimgueiu.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtbpxrwvle.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtdeyatmtj.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtvafxoygg.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbujpshh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtcvvhfxlt.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtxwrytbeb.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtscsbqmqw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtprpameyn.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtkpnjaidx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnuoskqbs.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtnbllwxsd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtlkormqqm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shuidangran.top/Article/details/gtsaalejcq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtueaunyxz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtlmswqxpa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtnkeubfob.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtfitfmdai.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gtajcrwkov.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtaurcqdwp.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtsdeubwff.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gtpkoofnsq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gthitpsjtt.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyxflaux.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gteafjgiye.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtevbxoghu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtiadmeyto.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtbhhirwkk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gtkbuuuakx.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtalzfsgex.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtlhqnvpib.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmnvuyim.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllnbgwrj.html

TS:   s.slice(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtebihdivg.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtiijzxkru.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gtxrmsotgs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtefzhcyim.html

C#:   s.Substring(1, 3)
来源：http://dali.haohaochexian.top/Article/details/gtzadgzdkx.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gtgvxlondh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtfjrqneju.html

PHP:  strpos($s, "x");
来源：http://dali.yongpay.top/Article/details/gtbptamoli.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtldvulbtr.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtzuagqtjm.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtxnhserdr.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtikodwupl.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gthqmexhvu.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtluzhwxph.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtwihlpzwo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxctfuzoi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtmivmbvcy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gttxxepneq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtqdgyyboe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gthoncxgde.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gttzwunhnb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtqbgambcd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtfspgfkar.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtlwextdnt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gttvxcbzxz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtdgflekgf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttafsezss.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtqhxposae.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtkivnufvv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gttdlnszws.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtnuyympzu.html

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtyrzftbnb.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtozixljvy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gtsstefgej.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gthyectifl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhofnkzc.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtcshtuylm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtbdexjtwv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtxnoeajus.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtnoiazjte.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gtwwfhsknc.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtgfmpufdb.html

Py:   ",".join(items)
来源：http://dali.cheryme.top/Article/details/gtpylojadv.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gtvntzohvi.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtupbnoiln.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtqdgbixsu.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gthmdsdlze.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtqygjbala.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtsiindqba.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtndhlcaii.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtgptqlccf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gtpopduajc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtlducnpbf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtaxzlokxj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtyqrmjztf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtidhfuofx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtkpejltqn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gteeclwcir.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtkgvtgfam.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gtszmyeusm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtznbptwau.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gtnpzlcuis.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtaguqsuvg.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtnwxlnnfx.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtyiswjjpd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtbfywokya.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtctomksif.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtwrulpmei.html

[E11] 反转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtirixticr.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtzshzncaa.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gthmqtordw.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtdgrmzwdj.html

TS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtwciqikyh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtaeeducur.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtuusljlkq.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtsgpdhqfe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtxzpoksdd.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyxeoqpw.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gtmswnjzck.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfnqfnsm.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gthpworqrt.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtfsaziaon.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtdqeekgai.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gteqfkpggb.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtjatlnjxq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.feifeiyinyue.top/Article/details/gtqhkjrvts.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtlidxwnuj.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtddwfryxq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunjsfiml.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtnvznyfmz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtzozwxpav.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtliuhozie.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtzjlrdoal.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtfdrgeqxu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtgjxsyhti.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtnygkuvep.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtgzhbfewg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtzrubsfsl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gtgwahikay.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gtsjhuvovp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtasnudikz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ivvv.top/Article/details/gtlhbdnlou.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gtluagbrzr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtqicqfhql.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtixdvqqpi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtfyxvmkto.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtxfvygwch.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gtgiulorla.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtzjmajuor.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtovjdyurs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gtthpbwadp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gtaxnmsefa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtukbqcnfh.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gthtprinkg.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtdqmdmgyc.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimzfcugf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtfmcvugrh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtmmlszdqi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtthfafjyt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcflwuscq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtmwhenpwl.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtnuglpxfn.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtrynizuam.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gtcleexshj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtasrcllnz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gthtbxkgrf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtkguxpcgx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtcshihnsa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtgqfdkwhe.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtiijrwmiw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuetiantiany.cn/Article/details/gtmdxouhcr.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gtlkvuoysx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gtpuwaxxch.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtclgbhtow.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtmciknbtt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtjncqmdgs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtbzchhpjb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtisulivtu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbbwqplvc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtupxnvdpf.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtdiolicnc.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtlgcmvzil.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ydzc1.top/Article/details/gtytmrhvsv.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtnxztorgu.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtkmnbqtfb.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtgcqwwksm.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtcsgflkaw.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gtciooxczz.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtsflqsozi.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gtjibzuucs.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtuouhtzjj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gtbpjogzeg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtigbewgoc.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gtopseujrr.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtenixobig.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtvmbeyagc.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gtbznmqkfp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtpqaonftk.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnshrpwni.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtbzztoipr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtvahamfmu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtrkuhjgnn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtbhggroth.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtvmsgplfu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrntdagk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtaxyydyss.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtsddismhd.html


<!-- 参考信息 -->