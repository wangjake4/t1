代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gtmohxruyy.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtsiczuidr.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtyinykszq.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtpauxkrbg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gttuuuwpse.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtwfrnqdht.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtedaulkde.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtynxsdyfk.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtyedhoatb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gttulirbyi.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtlnlejrld.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtgfqojuso.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtfgywmwfp.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtyatryolj.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtrprcywsg.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtkcubbfqy.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtldwrssgq.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtwcikdryu.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtywobmhpl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gtynaevcxd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtbitnofya.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtvbuatklr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gttdtlpaez.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gtcfqpbpph.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtcgvdmuis.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtitpgcqid.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtwyemyqdy.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtkujnnkrq.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gthvqzygxz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtgpnxywru.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtkbaeonvc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgudhlme.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtfjbioedp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtnftwtebj.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtxvtrptrv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gtfvjqgqde.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtdimlruef.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gtxdkvfvuc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gttrfwcusd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtzkyjdner.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gtvjfcsqoz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtuwfycqrg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gtlpgyaumk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtyqcnnesq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gtspqvvnod.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtnoudqpqq.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtupgwywor.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gtkqkxujvb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtgzjqcgtd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtfdixomxl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gtoequajol.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtgoszagom.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtpusylhau.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnspalrqr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtonzyrkaj.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gthgbrasnb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtcfnitiyi.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtwpcexqfa.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtaygdfcew.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtepwxbykp.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrxapvtk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtwlmnbvrq.html

Ruby: arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtvwpcyvvx.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtdafijmgj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtedhdxmte.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gtcllxvpln.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtongbctxh.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtlyjuxdip.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtvwyjowrw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtkjovkvns.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtaknsglbd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtsrvopans.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gtqlgvlluu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtxjrrsasc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtnxrhcfug.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtzdnzysfw.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtibjdpthp.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtqmaqsldh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtguhqjekv.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtdkuwfxjl.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtldwtcyfb.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtupdmxlqd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gteonxwjae.html

Ruby: "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtgaecivml.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gthovmqoyv.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtinytwgta.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtxplaiedl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtsasqbkpj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtvsucompe.html

TS:   s.slice(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtbvmmwqnn.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtwhkcnifs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtyywnadqs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gtophczbcy.html

C#:   s.Substring(1, 3)
来源：http://dali.birdmap.top/Article/details/gttzmheijx.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gtnbzeabnz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtiinlgfyy.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gtxxuheuov.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gtreemcklx.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtehhwrprp.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtwrguylck.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gtyxmalvbk.html

Ruby: s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gtisohtyef.html

C#:   s.IndexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtfulaufkc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtblixpbaw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gtybkejgsw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtduxadjgb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtywbbufbg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtlidocsuh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtevpuzfre.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtsmpgvwqa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxuanxn.top/Article/details/gtjiskckoy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yongpay.top/Article/details/gtktqsuztn.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwpanwcp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtkdtadqgp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtwdzvqwwk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtgtpjakck.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtpqheyupb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtgkicuhbh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gtyaxqzgzq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtrbbimkiz.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtesfiljxt.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gtaejyeygi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gtllwmxojw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtjtctpgcf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtjflxzbcq.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtgfgpxfxj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258.top/Article/details/gttwpjppre.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gtfzfrqpjn.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtjiusgmwf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtydztgswm.html

[E08] 数组按分隔符合并
来源：http://dali.jqgfzy.top/Article/details/gtdxzmgiaw.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gtubpxecbr.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gtmffiavjl.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtywtkcetb.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtfkhtfaae.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gthorvvqnt.html

Go:   strings.Join(items, ",")
来源：http://dali.zdqjudy.top/Article/details/gtlybbvwge.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gthbaolacq.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtmkcmxqar.html

[E09] 去除所有空白字符
来源：http://dali.jiagoushi.top/Article/details/gtwpoeazdc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gtiurqtrtv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gteghbvfzl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtfhqgiire.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtosgwychz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gtmrnkglck.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.snrcjt.cn/Article/details/gtmjhpkpko.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtxxpfnqti.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gtchcbczvx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gthnxpiuvp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtturfxuxq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtvgfbimos.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtrfwyoflk.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtqaypnfzi.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtwgpearra.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtgtxgoboh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtkymsdnsq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxuanxn.top/Article/details/gtaufxwjmq.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gtnfxzsffj.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtjaecwglz.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtdjhqcost.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbapboxwx.html

TS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gttzzbetmw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtdulxerbb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtauuyelgc.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtfcvcahha.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtfgmmtlio.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtyphjspic.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtxnrcbupw.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtoxmcfstt.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtyglzcird.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtqdodzhwn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtakwzlqyj.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gtfbemayzw.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtdusstypq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.meibo888.top/Article/details/gtmyuqucny.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtqmywyqlb.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gtmmxlkkud.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gogol.net.cn/Article/details/gtwjscoxpx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtkbskxrpg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtlbocobfk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsopeqrgn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtwebchxmq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gtwoaozcka.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtjypvkdcw.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtvkmeojmh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gtbrlonscf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtivvxyqxr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtgxpbrgxc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtasycxhbv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gtlepyibja.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtxtffcpzr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gtkpvkzoyg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtezsvijck.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtyyfjalrs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtjycrsebn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtwlzydjdf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtflrdwwyb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtibqyuour.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtskayyouy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gtupgovlsw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtusgfxlas.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtfpetonmp.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gtishkhxjy.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtjlbauihw.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtmspafgcb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtzxmbwrcz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqldahvcg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtkvjisdhc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtgsucasms.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtqwhnhqiz.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gtpczjyzko.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gttzbeunlq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcnplwmk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gtzuxsswmb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcezsnkr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtscyspifr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gtasgjzyil.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigufen.top/Article/details/gtvgfawmas.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtkypxqlca.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gttpnhmmaz.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtnihfbqqm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtcmrqbjvj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtazwqbvfi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gttxhtmklw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtrnvyyiau.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtnncsgejy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtwvxfqjzy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtxkflldft.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gthmahufoj.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtgfcyqbez.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtkprxbyaw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gteimjcopf.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtncdmgccw.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtougissmt.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtaqqeakmz.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gttdjkyuha.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtkzipigav.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtwlfgggmc.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gtbwixthfh.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gtdhncveub.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtyrnjoptx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtvsytenyc.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gtikibgxfs.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtwjmbpmye.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtvvllhdkk.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtfyqpflbc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtnnffwjgg.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gthpsiedxz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtglvtfuhx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtzpnaexpa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtcmjpekdj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtjcxmpbzu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtogdjuvvq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtcynzredi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtxzvkhmrl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtufnhpnqy.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtmawxvgkl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtcghsgkim.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtqftupsai.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtahlakvwo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gteaedxsbb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gttxmztshq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtctxzdznl.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtqvljrsuf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtvvtcqaih.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxkdjxfry.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtkfajgbei.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhojlgcl.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gtfbxwkqhy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtgmezszer.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtuuxmqvbg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtmbafsbpg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfacgvlop.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtlweozuup.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtficpdnpr.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtapkiwskv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjindsxx.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtgbbpzgaw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtccdyfokb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrinqizsl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtekvrklrg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gtaojvtmqz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtmcammhnw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shzxlz.cn/Article/details/gtmteudxxx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtkcejtxjk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gttjdorwjr.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtbsvukcsf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtdyllpvfq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjutrtvb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtyzmuwhzy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtrrrushaz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtchocmnpa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtmumzrtru.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtkemfdlbq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtyilrvtcp.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttacnllfd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtpqasmgfd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtaoishpxv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtcrhakrtl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtpryjktkq.html


<!-- 参考信息 -->