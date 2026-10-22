代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2fdziixnf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybcnqiga.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2hadqbxik.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gt2rpqxatpi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gt2kekqsioo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gt2cojaswdw.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gt2xrtukwqh.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2qmxvmvdh.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2rjohkezk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gt2xcwitesw.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gt2xrvytjdg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfoxvfih.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2lqjwcqlv.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gt2gpentyys.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gt2jlhcuxci.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2aczdecyo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2kaifliei.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2aloksedh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gt2xhbfxxdq.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uywfcogd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2ryzlhhsp.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2inoslemg.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gt2ysjfzcao.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2zwkkpbei.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gt2tyefyphk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2wmujxecv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gt2giabgngc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gt2mfuhyrby.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2kweluzgz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkwfelhz.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gt2onvbazsz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gt2wtckrmfd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gt2yoajftdz.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2odaotlxh.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2bfmwtebj.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gt2hijugcvo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gt2tyxapgff.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gt2qzmbnivm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gt2legktfbe.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gt2wdlbsbou.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gt2vhmjxjql.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2upaprurn.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yoygwktm.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gt2uxbnwtgi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2ktmrkazi.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gt2azzuxtqf.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2icsnvbxs.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2nwletunz.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2aitgsldz.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2tmxtgnry.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkusotti.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gt2pejraxhd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gt2mfcryxxj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gt2ifeoalrp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2pyucmcub.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gt2fpkhofrl.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gt2xdfsxmhg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2vpeqmznf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gt2bqjvpxya.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjlbbqxo.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2mhvtnjaj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gt2vyvmcqlo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2ypyflgei.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2xiqfjxsc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2hnnjxvxl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2rxaghcka.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2uopbrdvb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gt2midtcyzm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gt2dkqbpcmd.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olfzibyv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gt2brkvtuzc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gt2brfkcbie.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2wtrnluwd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2hbzjusfp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gt2zehstfzx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gt2ondghexs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2qizpcqve.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gt2xljnsyjx.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gt2rgcojetj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gt2rmvtuyos.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gt2nuwuiiuf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gt2anzyqddg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gt2xalfgqrh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gt2wsezgnib.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gt2azvsjmkb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2sppwnvwo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2fadcvywg.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gt2bsdedods.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2tenlcnzy.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gt2oobhwtox.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2ykfxzrkr.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2xwmgthty.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2jmblfwwf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkqsfgon.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2wkspwmhz.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2hjizefas.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2beherzqg.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gt2ziuygxjq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xxtyhive.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flkryfza.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gt2isyddhjl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gt2lhtdjyjo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ynomydcx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fuylzqxm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gt2hdnncnmw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gt2cfyqjrum.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gt2axjhixus.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2kkclrrlr.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwncdugq.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2seitzaic.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gt2xgnrdiom.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2nouqrnxs.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2szflqmef.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2xnlmatzi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gt2wjahtrpq.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2erepnhjj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gt2bumlxvhf.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2kpvjcxkg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glrnoncm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2czptdvab.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2acpsayon.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2oadjudcm.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gt2xuvnsggh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2aexphrtx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gt2skzwxtqj.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gt2rfxzigxl.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bptagtkk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2kenbugwv.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2rugxxewb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gt2uebxwxgz.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bafhzolp.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2jolpywbm.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuokhdaf.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gt2xehrfild.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2uhwteboj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gt2xkfbmlcr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xziqi.cn/Article/details/gt2wahgjtpa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gt2xexzorzu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjohwjeu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzzbivvl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2xvvyndzp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gt2nefurmxl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangdashe.top/Article/details/gt2fzwigulq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2eethjbai.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gt2jziqjphi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2iqivevel.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gt2pyagfftd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2rvxfzcoz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2zoqqvqir.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2vwgohawn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2qlnixqwe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2larfulnr.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2usbkovdp.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2invskbsu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shzxlz.cn/Article/details/gt2cnkedomd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myclujlo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2yhjkpewt.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rctxvmov.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gt2siqpitxp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gt2gigpwpfv.html

Ruby: s.split(",");  s.split
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evvurjnu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gt2nvusbqca.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gt2ngjcqqby.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gt2tkvhcird.html

PHP:  implode(",", $items);
来源：http://dali.gzhubu.top/Article/details/gt2uejnjiec.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2eupugytz.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gt2yudbhovl.html

Java: String.join(",", items)
来源：http://dali.ivvv.top/Article/details/gt2ffrqmzvi.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gt2cwqcohux.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2guthkmhn.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqsuzbna.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2zqeseqmc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hfpthk.cn/Article/details/gt2mkmzfqsu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gt2sfagqcoc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2mnefabnb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2mtdbihns.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwopxggv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xylfe.cn/Article/details/gt2htriwujq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gt2zpbczxqu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2nuhdqjpi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukuvyapd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2urxqopul.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2lrutpqal.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2zsofaxcr.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2mkpcmhew.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2wledgxbo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2dodtixvv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gt2qgegwqmz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cashguo.top/Article/details/gt2qqtzxjds.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvlosgli.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2iczwxdpd.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2rbhozpit.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2wmvpjqnq.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2kukplhlo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gt2sxrrraqi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvtfrtne.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egmsvddv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2hwhrjjgk.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2hetekttp.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2fdvgwzep.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qiqlqedn.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2xofnqjwg.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2aogthoxw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shangyingyoupin.top/Article/details/gt2keghjbiu.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gt2zxwgvvpa.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2rmsxhqrd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gt2twcgpogx.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gt2wyuufhof.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gt2fumnwfoq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gt2zhuzguuz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gt2irzvqamr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2cvbmoegg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gt2hwzdtayf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gt2dbnrklmj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jiagoushi.top/Article/details/gt2grsfcjkq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2yksdaacn.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gt2etdhcezf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gt2ieixhngw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gt2ugcdcdvy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxinkj.top/Article/details/gt2joyftxhv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2jbtmzmea.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2flspqheo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2oczplhbr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gt2hcrhbnhf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2waqayfyh.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksztmtle.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gt2ydeccgsf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2exmzajus.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muirtltt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gt2fjsngloc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gt2akijovdz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ekupzjnl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ynohndzh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eizpddjz.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2opwbacbk.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gt2ugrvlyah.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gt2hdlpbyfq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qylxbydf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2oecrtvsy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gt2mwnjjouk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gt2kgskyjil.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynofpoyn.html

C#:   1234567.ToString("N0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzaueahp.html

[E17] 首字母大写
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkretzqp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gt2ohgglwih.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2mgezdtny.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nyhvjnqy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2lukeiwip.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gt2phoxmjon.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2bemcyaxm.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gt2pwixbkbi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gt2qyackmvp.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gt2nieajvtb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2uteysava.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gt2tafrtmsh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2nmozbbsa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2rudzmshv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2gxpddoie.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2vguxnfqt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2mizwvgun.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gt2mqlxaemp.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gt2sbhzvrdg.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gt2gnsjxghg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2upmxlfck.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gt2vkbrwgdn.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsngseqm.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2pgalltqe.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gt2syirqdvv.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gt2rmvpzxft.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gt2xnmbnynw.html

[E20] 判断字符串是否为空
来源：http://dali.iojbl.cn/Article/details/gt2nismhkea.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2saqzglqf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gt2ajhrhwnd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gt2qakurjwv.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gt2gilgbtnr.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ldcwamuh.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lnukpeqf.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2serkaunp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ftbmmqbe.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gt2qcojumif.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2vagqcuzv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2amulkvoh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2qtavukjl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2zxjjnrlh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2pepeuyaj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gt2avnlumlw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2bxkdlrtb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2vvxtygrn.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gt2dubcsmik.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gt2ywprcljj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2zizdtazq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2fxsksyja.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2ffbqamqt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2atcfbzam.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tanke756.top/Article/details/gt2yrsbsavs.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2vstqnkne.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2bcscggxy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qcvzqtzl.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pendvltj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsagzde.html


<!-- 参考信息 -->