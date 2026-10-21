代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtjfpmnwtv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtjcowlyoh.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtmftcorlb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtfkeptitd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtblvcnyit.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gthavmksna.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtftttbokm.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtdmdoljei.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nwbrower.top/Article/details/gtkkdcdmen.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtcdergtcu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gthigxqawr.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gteubtkejt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtygrhsufl.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gthooopxxu.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gtbeaznhat.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gtkbcywybt.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtvjsgofuc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtqclyfinn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoklslouk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtttiwesqm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtghxpldrz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtehfbhgky.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtjdwxxngi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtrpbzbyad.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtogsqjggh.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gtootivklh.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkyeqsutz.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtokkssbma.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtzefmjjvw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtjnajqarq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtjarxlige.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gtkstqsnjw.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtbuzvznmp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtbqhubdpu.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gtfcittvfo.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtrugeolro.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gtblfycjfh.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtpsnmnpvg.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtyxmgtkzz.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtuuocivvs.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtklbpdjby.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtzllgcqoo.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtesjzrgif.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtjzixlior.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtmslkgiqv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gthqzxdgiw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtspvqgxaf.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtjjxfjund.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gtqwteobak.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtgsijtcut.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtdrbzuoqi.html

C#:   new List<int>(list);
来源：http://dali.316326.xyz/Article/details/gtmkemmfsb.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtvfmsmwvm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtcrnpbpna.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtcwxngktg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtevveiwlx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtnvkxcjgi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtsacdynsv.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtkyncbada.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gtyrlybkuz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtzgnjedxa.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gttrpwcaxh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqxswgim.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtmjavesvy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtnbyzajgl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gteuilxeuw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtyvqniqid.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvbdgowh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtyiruwikw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gttwknqfvn.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtpjonlmpw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gteasycrix.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gtspiwewwp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxehkbmno.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtblaexwen.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtzwauudqp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtkhqxqlif.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtkikjtuti.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gtsvubpnml.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gtfovcqgzu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gtnehelnpl.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrtdcfxs.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtykjaijyq.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtklxceaqs.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtpgjaatkz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gtwirvmqlf.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtjihnbxpl.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtrcqiilal.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqoeqedsi.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gtrnlrncvb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxxjrbkjb.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gttpqwgmkf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtatndcxfk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtehpcggyx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtbsaznhkv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtdzatjtmw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangdashe.top/Article/details/gticzvafqk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.haohaochexian.top/Article/details/gtzmbrdmdv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gtbwvlvipv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtobwgsvcn.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gttbtbygwp.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtzskhxihm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gttfheyceo.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtgpkgopxm.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtoqinammg.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtrbxxaccg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtavcmegbx.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtiuktzkfx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtwesysdmk.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtfnwfqlxt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gtwlwprcnf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtbpzxolir.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtgivdbkad.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtkelxtask.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtmascfjyl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtntgcdoba.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gtiiltoozw.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtxdfhcpzs.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gtbkwpdyce.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtfdastoni.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtbpgukckg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtwctlndve.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtbsnwyitu.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtgsfqgwhx.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtbrcnlguq.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtfnxvwiaz.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtbpylczww.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtvuacvryh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtjszhwhjo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtusxrcsgj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtyjkrgvio.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtuqcuswjw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtbjsmmsqb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtrpghsecx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcskvjcsd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtxsraioqu.html

[E06] 替换子串
来源：http://dali.zhongyouzk.top/Article/details/gtpnzviycu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gteexxcjng.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuanzx.com/Article/details/gtpjbtkupj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohfuumjc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzvewyub.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtspvgmlax.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwefladbr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtxwwvakto.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gttbakneko.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gtqhagxcun.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtrhnxabwg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtcysartnm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtyckpibtl.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gtrapgmwwh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtxbfotbwd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtomldgfco.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gtmemhewku.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtljocmqbf.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrecbtea.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gtxcehbotz.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtyfggvsca.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtoyflbyft.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gteeatrrpr.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gttxwyistl.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtgmnoomwm.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gtnywvhrti.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gttucxujyi.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gtxgzzzwir.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gtnqmgxnkg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxjjtfyh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtejmbkxca.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtcowgsnlx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtoomkcpgm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtoflkjfuz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jianghu66.top/Article/details/gtpsaztxne.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtubhcnrdn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gtlnefjbxp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtxulqtuuw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtzypmqpma.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gtjykiymue.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtnldfjkjv.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtqispbeku.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtvfswethu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtzuiqkjyh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtntmkrmdo.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtmhzhonhf.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtytgiirdn.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtqovmheru.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtkaeonxht.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gttlcahrvt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtjtxwuspl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtsmfofzbk.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtsmbslgng.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtqnjoxvup.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtsolktygt.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtjfralzsv.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gthnuczybf.html

JS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtoyheiqoa.html

TS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gtohdrylfp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtfmqhklkk.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gtfhtopxdk.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtfcxqbyxn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtnauocnhp.html

[E13] 逐字符遍历
来源：http://dali.hysaishi.cn/Article/details/gtlqkefymg.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gtvetxucfy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gtzhaakhdj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtaqiqlnjk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtppckxgno.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtrzrpqqmi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtfgksrict.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gtvzazbpcg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtqrqrowlu.html

[E14] URL 编码与 Base64
来源：http://dali.0kj1m.cn/Article/details/gtfyjblicz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtzkgtnpju.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtzokkspmp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtqohpunmr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gthvrriilx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtycbtrnie.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtvdtqpahk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtaycuyziv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gtlndkhafe.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtggshzrvd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjacskbne.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtyaxcpavy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gtupqqbqea.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtpyioicav.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtiapoudkw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hfpthk.cn/Article/details/gtswkohevg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtihbnnskt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtsjkxyabl.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gtckrnyghp.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtgscmyzrv.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gthyrbplzs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtyxefmeva.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gttxsyjiyy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxdsxnqm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gtablbfwyl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gtuatiyuqz.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtnnccbypk.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtwbdjqtxh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtajuluqim.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdszvzeki.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtpaopadwn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtxajadwyo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yonumen.top/Article/details/gtssizvsac.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtvmltcamn.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpjgilbw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigufen.top/Article/details/gtcmqgaayz.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtephltqjm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtonyjrnxr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gttsfatcfx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gticqpiufi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtmxwapmyf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtrejtddtk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daxiang520.top/Article/details/gticmfffdj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tianlin.xyz/Article/details/gtgbcbhudm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtxcpwmhcu.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gttiaivlrm.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtkfylcuva.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtdqappuah.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtdvbspeev.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtildymgqe.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtunbmyash.html

Go:   strings.Split(s, "\n")
来源：http://dali.gaohongyu789.top/Article/details/gtmsljfudc.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gtcazlpvow.html

C#:   s.Split('\n')
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqrvlidm.html

[E20] 判断字符串是否为空
来源：http://dali.vqdsnc.cn/Article/details/gtktnjmfwm.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrygrxsdy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtokaqtsdh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gteoibagcu.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gtnqdoeykt.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtfaarmrdg.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtujhnvjml.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtuiosuxum.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtskguizrt.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtvtkkmsyd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtrchmgdva.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtcwzttlwe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtnppbnlay.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtlqtrdpta.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtugrrsgkt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtrevwsmhm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtabkyfnuc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtngpyohkd.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzrzwoph.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gtyvltkfdk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtawzuqxgb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtfkhpvfhd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gthinwybkt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtuxbjaarc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gtycfatjic.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gtyoalsfce.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtzhprljvy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtebxrnytw.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtuizjlxjr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzxswwjft.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtjxjbqziz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtgxmlgova.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtvbfmfguh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhengqikj.top/Article/details/gtzqsffjok.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtrhqhljou.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gthbbkticw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtuchxiwen.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxuakpxxc.html


<!-- 参考信息 -->