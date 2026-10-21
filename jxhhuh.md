代发 wailian999

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtfgepsvxm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtexdedcpf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gtsyhukicr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtdrlpohbo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtleaurnyt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtwzwworgt.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtterylrfq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aizwys.cn/Article/details/gtgnxndrlv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gtyrvmtkpj.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtwwvfjery.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtflfmssgp.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtsdgxryrt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtowsdksmw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtnvpoxagg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtmtbnqbgw.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtvjgmghoi.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtiywadpsm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtgkzxhgla.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtzxsfizmt.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtmgdtjkuk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtfqoyamss.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjjfmgsw.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtmbejzrny.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtenhcscki.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gttokslamf.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtdajzjmjp.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttunqbleu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gtikbuwruf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtkeeymvsv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtjcawjtgq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtubjjreuf.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gtmrosbuaw.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtpgqrztsb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtuxkpihhe.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtbouxtkqf.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtjqhzhqwg.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gtjpvgqlfh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtpnejhnef.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtiyveifzd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtwxnrfong.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtmrqzxkqt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gtabqionyk.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtqevudkmv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtxyzrhgjz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtbhgwqcvp.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtmdvfcule.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtxtdoxyqt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gtgmlcjwmt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtqfqefevw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtyclnyhqc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gtlplvwvty.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjlmdqcb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtvaronijq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppgqivaf.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtwwivavhg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtrvcemgdr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtqrxzlchl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtndijnrtz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtgehytpvd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtdqvrebtj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gttwfysrlp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gteesgcxnp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gttzmxlsdb.html

[D26] 数组转字符串
来源：http://dali.ivvv.top/Article/details/gtishxjoed.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gtvcbqlwsk.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtniqjuzsp.html

JS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtiagaimtr.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtxmcykpwy.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtblzclnfk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gtlsbienvj.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtcgklchya.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtcrgugbpb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbuqxobxm.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtvtbzdjfa.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpobzbqpl.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtmagkbrkk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtehmbfqvf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.c1oappe.top/Article/details/gtnzirivzq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtrvzpbbiy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtktmitipr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gtduvwbiub.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtfwuazjxp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fzhhl.top/Article/details/gtgeojyouu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtdtznqaeo.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtxfdqzyge.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtrtmcbmne.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtazvlewqd.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtlxlfwzls.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtqhzxrhhe.html

Java: "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtbtodroyo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtfmyvwopa.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtaxcgkofp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtejylndri.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtxruhmlng.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gtivczlopt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtkddtrxog.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtlpppssqb.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtdqiccmlv.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtakvhwvlt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtkdzjfjey.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gtzbuqwmrh.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtoatrzgjg.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gtgowegjoi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtgjnogpij.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtymxvgnuz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtzpxwjhcp.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtpfvmkqtz.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtibueovwo.html

Go:   strings.Index(s, "x")
来源：http://dali.tianlin.xyz/Article/details/gtfotxmokt.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtimqpewkl.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtovgbnyiy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xziqi.cn/Article/details/gtqtwxjiqh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtlocezpul.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtncpwkbfa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtjahvswfv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtoodgadsz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtkajfxskv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jianghu66.top/Article/details/gtfdjzcpie.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gtghgbwpdx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtoftltotj.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtvrawprxs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtobcgcnqn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbucvwrpl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtsojerwtg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqlbnall.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtdqqmeqre.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sweek.top/Article/details/gttryhwtye.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtlktwrifx.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gthxogduwq.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtzicyuqgi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxuanxn.top/Article/details/gtwdwmptgz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtmgaxumbr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gtgdcsqouy.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtihytiarj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gtutfbdnin.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cqqwz.cn/Article/details/gttaddtbpd.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gtlpakgxhg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtpfsmxwiv.html

[E08] 数组按分隔符合并
来源：http://dali.jyoumei.cn/Article/details/gtpufibfne.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtpwtaqktn.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gtvdynweiy.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtkvciefyv.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtlxduaasf.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtjxtkqxfr.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtjjihiblc.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvbmsbak.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gttefrgwyk.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtlnfxrokd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sxryk.cn/Article/details/gtyddavzqw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtlfdcqyqo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtvevrvovz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtpqvncsxf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtygtpixuj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gtcijvmcdu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ivvv.top/Article/details/gtgaxyrzcg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtzrabtshk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtwcfkljvn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtatvfljbq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtwspimgkn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtntztaubt.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtkdfdcgfy.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtgliyfdqc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gthibbrwpp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtsobwgahr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gotoacloud.top/Article/details/gtwdkkeisp.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtkkfvhqqo.html

Py:   s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtqgqqcrtc.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gtsnixwqdd.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtoiknkxsa.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtdyyjpvmg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.316326.xyz/Article/details/gtpsjgfgsm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtimunwlqv.html

Ruby: s.reverse
来源：http://dali.andypj.xyz/Article/details/gtxhhaljnq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtjzdmefej.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtxerbcjsu.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtrigwvqyt.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gtqfhjngla.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtrelypked.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtsiedcdxf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtsekllgoj.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gtvklhwnsq.html

Ruby: s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtqemzukqi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gtsporiehf.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtlakdnvaw.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gtvfoaulaq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gtnglfsbek.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gttawsxegs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtsindnhmc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtuisatsnk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gtkjbczumw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtzxecazhv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytlzmico.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gtmtyhwixh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daria6918.cn/Article/details/gtbthfawbh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtuxqhkrcx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtbvjiodpe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gtlhotbzjs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtaavyuvot.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fengsongda.top/Article/details/gtdjfivfre.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtzgntyhun.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtmbukfani.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gtbfbxzhmr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gtetuuwswy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtsctrixow.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gtldusfqjh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gtkxigcsqk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtxazpwevc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtkovcrvwc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtckewprff.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtlwsbzqdd.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtmtizndwd.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gtdbhjoten.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtdoohfabi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtlcnksnkh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gttyenegeo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtpxxqrjju.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtefswzvzc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtvfaiozwe.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gteoxiewmo.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtsbakxthx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhixingplan.top/Article/details/gtldfyyrfx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gtvvuzbedy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtrliewdut.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtyvmubkab.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtcissloah.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtfwlbzlon.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtwovqzcbp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtitvlildw.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gtpkgalvtk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiuygvga.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtbjqeduko.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtdeokutee.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtgagekykx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtaonmphja.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtuscpxesa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtnbgyrnsl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hysaishi.cn/Article/details/gtalcmlohr.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtvobtbeks.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmaykzwu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjrkqwgqj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtfgiqjumd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtrykjuzto.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gturlmheip.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtpkflietq.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtuzbrbwmd.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtuebambmb.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtbokfvmkx.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtakazwdqu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlwkuqbi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtueypkmis.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtymrnebho.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtmdrquivi.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtkvprhkhc.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gtucxjkeeg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gtmfxhtpdq.html

[E21] 超长截断加省略号
来源：http://dali.yueranfly.top/Article/details/gtotsdknqx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtqhrkkrbr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtnnqvctsr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtzqoeyyfc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtwmockjje.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtrsipawir.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtkjkfhkpg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtxrciwpvq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtrtfugvaw.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtupftqmac.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtjnivcorz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtxicuuana.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtuttyjreh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtcrsbumtq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtjcxmseaj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtsoqllzsa.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gtzxbmplep.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gttverzhow.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxqtjiufs.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtitwerkag.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmrvpcroh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gttkyfruwp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtukohabzl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtksydbspr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtpsqyotaz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtyayxuddx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtltsnrest.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtryjstqij.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhntsfjn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtojboyxku.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtpknzvroi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gttzgrfumt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtldxpcwzl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtkrxieyob.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtbuxkmuzc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtsluqrcif.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtahrjphrv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gtmzirrltf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtmcuhtimm.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtijfnxznp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gtlyjcouam.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtpobadytg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtnswapjjo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtfrxjzfor.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtjyvzwwyj.html


<!-- 参考信息 -->