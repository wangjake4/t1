代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gttgjlqyim.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gtjngxeyhb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gttqywieeh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubjkdzcy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtjipxfebo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtfdikptdg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtxksjhtlv.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtcwgopuum.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtbziqiwfy.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtstdrgyao.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gtdwfvaqsp.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmxwayfom.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtxcazqwex.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtbailxomj.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtggjfcacd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gtpcvbpmts.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtwkfozahx.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtoeegujpw.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtjhupgpwf.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtzeisfktf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtxzdtesfs.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gtoqruheiv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtzbpnxqmh.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtuqzrpcla.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtesvrmyrn.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtfyzkuowu.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gtawecnkzf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtrghkuuwk.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtdzdvmgyw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gtrsvbmdys.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtqxpogxkg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtzhgejxwb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtgfepqyga.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gthbxmmatd.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gthctgifep.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtwzvrrgsp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.snrcjt.cn/Article/details/gtdjnqfvto.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtkrarlahz.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gtxfednqtj.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtkaaaqnxn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtweotzpdi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtpsswjdrr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtmdbjflns.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtkhhhbhul.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtvdykybgz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gtyfxhhjaf.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtxwgblt.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtesxifdlg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gtcrqrklhe.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtrzbcqwcc.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtgkndbipp.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtgeazibfa.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtmykcyagc.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtfpzcsqxn.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtzqdsvxmm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtuqiwrqfp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtytnmrxrz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cdnleiting.top/Article/details/gtkwwidfrg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdohotan.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gtzowtjbbx.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtiuwbugrg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtxgpihjws.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gtvidvzzxx.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gtznpykvuw.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gtrmqgzfna.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtnjkavytd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gteyvliacm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtyumjzdnr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtbmwpcgew.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gtbcbvmywx.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtrykorpcd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtmwedrkew.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gtstiyrhdm.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtyghpckdz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhypivvw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtononvavp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkrmyptg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtvlzawyuc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gtvpisglqw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj202588.top/Article/details/gthehctoyv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtloddwyta.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtnknqvbjx.html

[D25] Set 集合去重与交并差
来源：http://dali.sysykeji.top/Article/details/gtmexwclcp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtuxlvsiyr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtxbbgvvkc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhongyouzk.top/Article/details/gtlctqmwub.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtvwedadlx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtnjdicjwr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gtokuqeffk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtthvtiagd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtbfimrozw.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtrfqmofyk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtogrwazbz.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtiagblgde.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtbsrpqhtu.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtpgxmrehm.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtguiuitph.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtuqfrnsld.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtrcdpisjm.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtraivzndz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtonajaggf.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtpwrhnvmi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxptfbvqj.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtkpprtrrn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtunmpsrsw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtmxoyojow.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtkiujsoey.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtixgtaijr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gtpqcptyjs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtnybaiiuz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gthjtwpkhc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtfglwwqfa.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtejxiphbd.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtsbjwnzpd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtndbbthmv.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtnkvbkcdc.html

TS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtuqadbolu.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtetzcytya.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtwfxkzqgw.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtqpsxkkby.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jiagoushi.top/Article/details/gtutwddnvj.html

[E03] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtdtndchpr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gtsqacpmco.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtvdvowqyo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtryjqjiin.html

TS:   s.slice(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjoyahii.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuxnomnf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtvnuqvsqf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtdqmvxbdf.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtkjtasuoh.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtahrjdewm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtvkqipuyo.html

PHP:  strpos($s, "x");
来源：http://dali.meibo888.top/Article/details/gtaduiptdd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gtdzanjvcf.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtdfupfctq.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtkfziulto.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gtraenspwh.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtfyictavb.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtsjohqwjj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gtlyusfxzw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gteekyamvj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj202588.top/Article/details/gtkhnqdyiv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtxtyhjujl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtnzgsdvmc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gttmqrrtlf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pengpengdd.cyou/Article/details/gtgrmehqpi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ppjwa.cn/Article/details/gtjgamtric.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gthggdqqta.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gtqxopluzt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtjgmshczj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gteswshmwu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtmacfnvsb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtmboehfws.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtueqbuudc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtcjaklafr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnintcfvb.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtslhkvqsl.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtpalvcces.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj202588.top/Article/details/gtzmlhptog.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gtlmogypky.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzrpbruym.html

TS:   s.split(",")
来源：http://dali.zdqjudy.top/Article/details/gtarbsbbcp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gtifqqkmve.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gtkchbuqnm.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtqyqmnrdn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jianghu66.top/Article/details/gtleocvebo.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtooyblfjg.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtqematzpz.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtpnbggvem.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtuweykutv.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtwbjlyfho.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtzsvlfhot.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtidxthjmm.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtthrdfmox.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtuxeomkkj.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gtpcrflbnq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gtinpydkng.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gtajnwtbpy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtitzbpsyg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtwmgimftz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gthdumllez.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtvuocrmnd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxuanxn.top/Article/details/gtlkbuyexb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtzxukjemp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gtdzjystna.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gttndfhxqy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gtmaoknpff.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtlcaapywb.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtgvvyrofo.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtrozoxaid.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtvynaepnf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtumxqoyyv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtsrlfucuy.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gtoryrnlsa.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gtdykpfqwi.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtehlonves.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtfujjeonw.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteunlxsfw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunkvbqsb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtjkwdatcr.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtkxzfwypc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtghfvremv.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtctmewhli.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtuqodoeiv.html

PHP:  substr_count($s, "a");
来源：http://dali.daxiang520.top/Article/details/gturljbzdm.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtsowpyzcu.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtwmdispaw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gtbqntwurf.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gtlkgonqyq.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtixzmkzwo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtiwtlerqu.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtauizihmf.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gtfjquezpd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfryajhy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtoiwhrgux.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmagyinda.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiagwasxm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sysykeji.top/Article/details/gtvdvgswaj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtrxygoyrc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gtvyczbnns.html

[E14] URL 编码与 Base64
来源：http://dali.sxryk.cn/Article/details/gtistszifc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtacpojlrl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtfypwbrlw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnqzz.top/Article/details/gtbwihnuae.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwcsjohv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtcwjemxxx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtytgvrbmb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtboirifhh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtcspardyb.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtewiiyrtj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gterfmojge.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtuapzxmyh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdbfsnasg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gtfwybhngk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtetzsabxz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtqkopsxyi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtrgctutig.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gtonarogyv.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtbouoyyzp.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gttydlmdic.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gtfrtdlgrl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gthnjmblpf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gtuavkooaq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gtqbpyqfns.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtmhnajuwc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtdpxhitou.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gtczfzrltw.html

[E17] 首字母大写
来源：http://dali.xuanzx.com/Article/details/gtefatwltb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtkmagnymi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtqgnqyrez.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtvxprprrj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtfupikktf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtxmbexsws.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gteddksnvd.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtgeyowigg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtzvugjefw.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gtzkfdsgwi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtzdwdzhwx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtetppcfik.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtvbiqxabb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtevrgxfsh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gthwjmboqp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtanwmajqc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtxqakahne.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gtduymebix.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtfmkcfzos.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtcqhmknba.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtuibzajog.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtajrkqjsx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtaugtwgnp.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtuetcxrpb.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtnkeillwi.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtzzenwhek.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtrblxodzc.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtncgbjsqz.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtscuycomc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtxoodhtoy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvhjyyqap.html

TS:   if (s === "") {}
来源：http://dali.zhiwuduotai.top/Article/details/gtavmtnrxe.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtndxnwqpj.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtpugvzjpv.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtinjeldlo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfihtjfr.html

[E21] 超长截断加省略号
来源：http://dali.zhongyouzk.top/Article/details/gtulmvvppy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtkykvicrz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtmyuassct.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtkoduhamn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gttvmbfjwo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtokfxaflx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtoyamoolb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtmuurjrso.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtatmxhkdg.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtgylawrqr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrutbkfw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtxghkjvqd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtwsxtdsci.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gttvzqsbhv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtknvndsng.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtyycicqpl.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabaxvowk.html


<!-- 参考信息 -->