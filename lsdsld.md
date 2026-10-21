代发 wailian999

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtyglgdytc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtoygwuqzb.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gteyaqhyps.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtsoohkntm.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtqaeakdlf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtyznghvdj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtiedurkco.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gthetkpziu.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtmkskfnws.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtobadbtto.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtqisobahe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtwmdsdcym.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtxygppnng.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtrxuyxmca.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtsqgvtfdm.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gtzywphyeh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtmivjiuyw.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtxbwwdgqq.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtygbemmcf.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtterqpshk.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtlqmqzdeq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtgbiaygxe.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtztsaaoun.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtsdxzhvag.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdusenscu.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gtwbuznpkw.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtgpqjshyq.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtxphhlscj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtueycckra.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtwytevsfe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gtwheblgqm.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gtdjvfvxzx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtzacrosui.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gtdyasjmfh.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtqnejtjae.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gtmgvnksfd.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtckjjtwug.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtdiskgkdd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gtstqstego.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtnouuchrr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtscdhzlba.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtbbzttbnt.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gtizjanfve.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gtbdjwfgrj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtzbnryfow.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gtzvhqghdi.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtgtesukpa.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtegftvjki.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkawfsqtz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxernfcw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gthtovkuvg.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtwsknabcs.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gtfhktzilw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtwabiuriv.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtkhdyassy.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gtqzafhqwn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtkuyjjsqr.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgkikrnet.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtuwspqfkx.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtyatsxfqm.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtucnpifqb.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtaeruyggx.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtkvmrdzkt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gtujgbitsb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtsyjmwikl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtjsldphbz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtaadlbzie.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtimoojwbl.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtuozefdci.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtazsvmhdp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.iojbl.cn/Article/details/gtzvurwayx.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gtojoktoeh.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gtpsgdnejj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtjjiqqyim.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtugmqerin.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtderiphun.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihupalyv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtbimcdzrb.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtkqleejov.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtbpkxysxh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtakkqubge.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtvsjscikt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtrivnwbcz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtlfmylrvb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtrklyyubl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtvxymcgcq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtbxyikypa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtjtgsvnrt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gthrxrotrx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gteqdanbuy.html

[D25] Set 集合去重与交并差
来源：http://dali.pycfn.com/Article/details/gtthvazcgg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gtjprfxdby.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtamibnvrc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gtrwzbiyio.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuetiantiany.cn/Article/details/gtawhtngua.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtaragsgep.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gtuyimfkbx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtketwumfd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtserykizv.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzynlzxkn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtuxhpqzsp.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtefepfohj.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gturakpqdj.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtsmnkvmbx.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtyimmnvsz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtbxxsyxkx.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtftukefvq.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtlxpsatow.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfexawzct.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtvnmrqfai.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwkgzbtkt.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtkqgzbnew.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gthwptkwxz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gtqriwsruv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtowdzzhes.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtlwsgwvya.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwwzbnhb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gtlilmooxy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtcdohbkuy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtxlsboseh.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrbudjik.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtjmfjcgdz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytzyndvz.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtgonkuxxq.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gttfhqcvhh.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtogsktaut.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gtniephqpq.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkufjhion.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtzsdnxhta.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtkkvhhcou.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gtzkmhbksa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtloqhsdwr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtgmcnsccq.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtwrgxookb.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtbjyhcqsz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtlwvbvwfh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gtlixjqgjn.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtinpquysy.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gtvqpkthmi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtlyiltdar.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gtpwuqguaj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gttazkocxi.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtvjayyxmd.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtbfcvsjcb.html

Go:   strings.Index(s, "x")
来源：http://dali.smart0.xyz/Article/details/gtdgkltyaq.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtfrzhpmqf.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtjsbfcoqw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gtkemkhphr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gttjfaeugr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gttugvrxmv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtboxbodla.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtvgzgvzhv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtjdwlvehj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.iojbl.cn/Article/details/gtrrpixdhx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfetdake.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtnrhlguph.html

[E06] 替换子串
来源：http://dali.jinqigfzy.top/Article/details/gtuxxnpnhx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtpycxifvp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gtruabooaw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtjhqulotr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtkgxfxehh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtgbwthklc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtszyrzwru.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gthceyfiud.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtmbnzeopu.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtxytqgjor.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtocexfrju.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtdxkzmhew.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiucflmp.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtigheajoc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtwufqljfk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtybmcbogv.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gticvrvzyx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuanzx.com/Article/details/gtmekgatwl.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtomquuqzx.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtrdfkfkoi.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gtzwezszxb.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtotzjkmdo.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gttmqoaaqy.html

Java: String.join(",", items)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwkfrtea.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmibxyspx.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtsstdjlul.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gtwgddqxwz.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gtnieiufhi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtlweixohh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtsvjwxpze.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgocthotn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gtvuuzhlju.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtrnjyrwps.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gttycalyll.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhixingplan.top/Article/details/gtesjhyfsi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gtmbdkwxeu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daria6918.cn/Article/details/gtvmobeque.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtyujzlgso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtsplpvwij.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtvvdfvwzl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtmgyfmmuu.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtzzvvjfav.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtzuptfyla.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtowodrtkz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtsiyxbgvb.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtejihqcpl.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbtownbb.html

PHP:  strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtvpmbgalq.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtpdwohopv.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtvljjmucz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtdmdoczht.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtnrdwgywk.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtodrvlqxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtunwbiesp.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhulghem.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtrraxqvlb.html

PHP:  substr_count($s, "a");
来源：http://dali.gogol.net.cn/Article/details/gtajmouvog.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gthdyjuhzf.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gtwszqgpts.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gttllytvdg.html

Go:   strings.Count(s, "a")
来源：http://dali.hysaishi.cn/Article/details/gtvwwznslx.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtekdanxnj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtckzaiqpb.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtlllowboy.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gtvmeycktv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtyuzqykgl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gthibsmoyj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtzuwhuace.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdeaouuz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtwbbynsxi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gtldmmsdud.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.smart0.xyz/Article/details/gtfgitocnc.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtgajgcnld.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtgjnhmdyf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtqsnrragn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtykobqmnr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvyltwjrz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtpzkmvmsl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gtcilgpnkn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthebbkwbo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtlmzfwbeg.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gtntqclaet.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmfjtyqmc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtxopgyzrg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.dashuyun.cn/Article/details/gtefzcndic.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtzbcfdric.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gtdynpgsdj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtycxoopiz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtmogtlcjc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtelxklwgh.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtqiwxzbst.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtlzxnrpyo.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtifmafxyq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtyudxtvph.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtruachnwx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gtgwptbazi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtgwbfpopo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gtajavfdsk.html

C#:   1234567.ToString("N0")
来源：http://dali.vqdsnc.cn/Article/details/gtkbdsoojb.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtkfwkhpwv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtdfpnidwd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtpgmrxtld.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gttqfidfmn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtwkruawtz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtzaiqknqy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyhrdpfa.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtqnvfjfgf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtwpwlhacs.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtdapvhtqw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gtthsnzqzw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gtyhyiiaev.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtomrgwiyx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtozogxmrr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtlvnbymqp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpnykyyl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtamxytmnc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtucgzczmu.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtmfkeonit.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtonxckilu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtsflyvatj.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtcpxnwyvr.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtbrupfktu.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gthldcmtyc.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtwlyanegy.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gtbptmglbz.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtofkftrrt.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gttuzzosmn.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtrdgzuhte.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtalqaanek.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtodzfrbyw.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtxowtjhnx.html

Java: if (s.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtnaexuwkx.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtufszaxvu.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gtyotiqaqb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtqnvjaocp.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtazbuwpel.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtpufesooi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtkymyexdu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtpujfnfre.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtpnrkkbkp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtcxhegdwf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gtszkkglzw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtnltcvlol.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtjxlcodis.html


<!-- 参考信息 -->