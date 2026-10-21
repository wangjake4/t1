代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtzkwnldet.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gtpizyagyb.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtglybvide.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gtpetebhfu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmzmyvbrs.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtnxpzrmcc.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtlvejsfdr.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gtworlfawc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqzrammy.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtznmtlzrc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtjipqnxka.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gtslmorklm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtpnswfnkg.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtcnakzcfr.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtsviqullj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtpwqxktru.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gtiydyyagj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgciiptkd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtabwlicss.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gtasvnivzj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtrrvdfqfz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtylbesunj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gttcuwbgzh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gtyjtkmjud.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtmzoydtkx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gtrscokdfx.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtikldrevh.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtnvjqjyzx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtaatjeove.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtithlizgg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gtislchoug.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtozbqtpmi.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gtxmldzfvw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gtvbursdxc.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeehynww.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtslmwpvgt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gtbadjufqx.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtzcxbswvj.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtafacqoou.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtifiqxqxs.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtbzvixdbn.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gtjiayivvf.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtdgohedqy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtoqxpczfn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkokvknwp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gtnvdtzhhh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtnduovwta.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtggbqtnny.html

Java: new ArrayList<>(list);
来源：http://dali.xylfe.cn/Article/details/gtztkfugev.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyznymyos.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gtwnrbhmtq.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtmsruqbgw.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtllqctghq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtjqgvdspm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyohibboe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtoyhpbyrj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtlaoupnpv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtjlibgawp.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtfjyziohq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtedjytgyi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtipjdfdiz.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gtuptifban.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtcplxddls.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gtufkavmkj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtihomvrbr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtwhodumpk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gtuupahfhz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtwwxzfcit.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgicvnyz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtzickjeto.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtdshreiwz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gtprdmhumg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtakfwvnwf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gtjuaetevc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gtgiokoxbj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtzxwzjood.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gtxhahemtd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gteqdqvsjl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtkxisdsbo.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtvpefveuf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtxdibyibc.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtudmhplbj.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtogqqatnw.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtrwmdjlof.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtfqtustmo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gtxslxnuux.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gthcpmmgaf.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjalyueic.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttbeecxst.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gtlbfhbekm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtoxhpwsbm.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtpmfxkwbb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gtdojwmwsj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gttxygryxu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtwjagbcxe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtfhbcqhcz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtvdvuubhp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtxvohpeqn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtnrjbxoag.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gttijdvrnv.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtlxcqcbxi.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gthwleiffw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zdqjudy.top/Article/details/gtnuwgvqjc.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtfncqlyij.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtnngdgofu.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtbdsrxwpj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtpbkukhej.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtlkgckqjp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gtdzzxlgbi.html

[E03] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtmtwmpjxj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gttpfanogw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtssqewpyu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtgddwpseh.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtoocetsev.html

Java: s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtshckwapu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtqhnkgvgn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ydzc1.top/Article/details/gtechinhgs.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtzlhoqnny.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtgzscfcay.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daria6918.cn/Article/details/gtojhzpwro.html

PHP:  strpos($s, "x");
来源：http://dali.yongpay.top/Article/details/gteyqlesas.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gtgfjvmust.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvfptvey.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtvnmbxlzv.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gtdwjhjhzq.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtsuwurvoi.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtpkkvgnxc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtlpyzqofq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gttjczolfk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtijfpzybw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtedgnvcrl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtchiafwir.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gtsrhedqvz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtyszfkvvg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsutwiaht.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtsbxxgdjj.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gtpgfzhzyw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtxllnfqrz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gtokrxyvfy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtaeezqrly.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtlhxhdyfn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtqojnesvl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtqurxxpnk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtiwfxhzzu.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gtetsxicdl.html

[E07] 按分隔符拆分
来源：http://dali.shzxlz.cn/Article/details/gtvhwwiygf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxrczhrs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtcokmdbkj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtamrwskup.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtqiloeuvi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gtycfpdlkc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbbicamf.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtivfzcxku.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gtgwtdjipp.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtgovqhrpo.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtexvfznrj.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtzkydngox.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtoicgrujq.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtisvhmnzk.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gthroobwmz.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gtiglzygmz.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gtlfswrmlw.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtsaiwznob.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtmhoulrkv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtfzoggiva.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtfgjcewzb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtyuevebix.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtgpfatwvf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtbtfetjsb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gtwblmkikx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhongyouzk.top/Article/details/gtmoembruk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqcwpwwx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shuidangran.top/Article/details/gtcqfzmpfk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtdqnykdid.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtvqdfbxrs.html

JS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtlwwednum.html

TS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtkbqkuhdz.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtetmcnhan.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtszzjvnxy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtcxrhgnmu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtiovqjhui.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtauwyvcjn.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtorlwxila.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtantfwmbu.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtmhudbgpy.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtiorxkpwf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtmqjnmjum.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gtybvcobjb.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtekduadpu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtokotsfkq.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtrwewwywv.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtluzozfgd.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtltqlggil.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgxptrfv.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gthiadfnbp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtxlegbbzn.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gtdkrhnita.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtwlyfqpfl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtxtzskqvg.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtydguiguj.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtklogxusv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtoizksphe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtmicbkbqt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtxlkwupnr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gtfcbqlqkq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtuuxqkeyx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtpnbzvzqv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gtbwgflbla.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtxyytsugr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtuwpqwxbx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtarxearji.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtfookmzgd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gtkdmnrgjf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvfncfvd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gtcaujxjll.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtmcycdwzu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtvlczkmxk.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtwfphzumf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtgrygitfs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtknzkiftu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtevxkeqvh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gthhucsnbi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gtgrftfnph.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gtvvijdzry.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtvnfhlqoj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtedggmkom.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtzuiuavkd.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtgwvkllan.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoydhoof.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtqjhjtyks.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtqunqujto.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtswreztcv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkkclhzq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtmvehwcvi.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gtapvxodfi.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtevvhfzgi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gthdgggmed.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtaqpvaebc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtzbnxnzgn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtvyhoitwq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtgmoplmgq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtkkfhwrom.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtblhfvkvg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gttjkoarvw.html

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gtygdukxuh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtirsnmpua.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gtlobdsuzj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gthsubcyud.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtbxvawfnw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtpesankvh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtqnipgeva.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgkwkiee.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtwgncwxto.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtilyandei.html

Py:   s.splitlines()
来源：http://dali.dianchejie.cn/Article/details/gtcvaqtmra.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkzrwcze.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtjdivjsjd.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtsqtrcyiu.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gttulxjore.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtbjnaruke.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gtmdtlvwcx.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtreikjwlb.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gtzuutobhs.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gtvylrmkgy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gtfevrqcle.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtlmsbqixo.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsgrshkf.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtofuoudkw.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtfgoavyfr.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtqjxkbqyg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqtnrnhxc.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gthqymgmym.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhixingplan.top/Article/details/gtdceayevz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtstauctow.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtxkpiyugh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgudgwrw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtfncusdqm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtmazdpuek.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtlvquywrr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtbwrhcpay.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gtezuunhnm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtyqxfguxa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtcozgsxpq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtmxchzlzb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtkxlkqbfb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtqzsxnsgf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtadyzajup.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gtndkoqpjb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtpndxtjql.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtocvlvhns.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtbfuqhobg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuwcogwnx.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtbhcestjb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtouplyxvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtmbtxlkts.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gttvcuxdjh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtxvtsmmof.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtoekaotzn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtxnikmwpi.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgtdqolvf.html


<!-- 参考信息 -->