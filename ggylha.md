代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtbaoqxfey.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gtqlcowccu.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtvrmxfdfc.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtgtygueml.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtqgmsfsqp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffdxvdls.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gtkvsxbodo.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtrufyclvb.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtedcdwhte.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gtnkpqjrby.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvkhkryp.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gtozhgkgmn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gthpzjzmsg.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtkksaddvi.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtkxrnxknl.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtjleibbse.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtqsmmbpxq.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtrdlopupa.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtjtjhgwrl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gtdaubgqbk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtbrviuyah.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtdyfqskuo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggxwwioj.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtgwipmixt.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gtxwtoshwt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtirfauqee.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtursvjtmm.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtzlqqoxfq.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gtuvtultxr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtwdmyoymk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gteuxetuau.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtbtjsrktc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtooaxbwfu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gtfmwjakrl.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtufmpbefv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gtxigqnmdk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtpkiiazxy.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gtzqevkccs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtvvodxokk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtadwaagne.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gtsgxtzqtp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gtawzsbzsn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtgezbhmpl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtnheyobdc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtzkmahjhu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtqexgdjcu.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gtgrbnbdqd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gtnzfovuou.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gtgaaaiedb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gttqbvqyam.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjaimkmu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fzhhl.top/Article/details/gtesosufqm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuxming.cn/Article/details/gtvbuuisvh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtsscgsudg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtigyuzuxw.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gthvxmhcip.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtcrxixgdc.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtlycluhie.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtczkfiwul.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtyxeztthi.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtufsuenro.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkzvbktw.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtrrzzhfxn.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtnigjnutp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgmaliqul.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtfziawawt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwcszhbli.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtjwjougoj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtwknzdhmm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gthhocyutm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtaqndohho.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtmflxtjps.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtvvneobef.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsnfaxud.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtruasnqmn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtaqbsujxd.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtbawhlryh.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtqzypuzso.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gogol.net.cn/Article/details/gtqpxrueda.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtfdfpzwps.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtghmfaanp.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtzrolbiym.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gtqjgsthxe.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtucctigvy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscdeidax.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtjcdtotbm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtmhtdophg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtecbxaxac.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtdtievlbl.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gtkhsimdgf.html

Java: s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtymehjgfr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtmogxihqk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gtqdwmcjyo.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtxvlvwzjy.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gtduzphlin.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtyxnwxhjm.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtycesebir.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gtmotxnmxz.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzqwtigi.html

Java: s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtlwacvcbx.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtiqueijos.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gtcivyanyx.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtvgpjtrif.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gtqwuxgnhn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gtxuvlhwcm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtxihjlpys.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtdagrhtlg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawjrdaqi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtfsvhrybe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhengqikj.top/Article/details/gtsdnjskhg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtcffjxwoj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtktbeckmc.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gthwsbbdnr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtawjieeya.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnirtnlwq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtjkhybfto.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtozkxpppb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtuyluagbg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gthomtvdvb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtysxhlcgk.html

C#:   s.Replace("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtwrreifvd.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvlbvjjp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtocrbcexg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtyouvfngh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yangfankeji.com/Article/details/gtfnhkdply.html

TS:   s.split(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtylenjqjp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtnxngmduo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtblszegsr.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtqzacdfpc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtxbfbvcdm.html

[E08] 数组按分隔符合并
来源：http://dali.yuanzhike.top/Article/details/gthygeqbdt.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtkgfonevj.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtjohqhhzv.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtanqownef.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtjlnriscv.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtqekdsqyu.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gthqkyrftb.html

Ruby: items.join(",")
来源：http://dali.yonumen.top/Article/details/gtpppsilze.html

C#:   string.Join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gtnnmtuvsw.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gtwybtmcoh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtdbkrjpkg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gtkvzoslfm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gttwjyznpm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtpvzzrxjg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtbgkbiwzc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtlynjkcmi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtfddvrufl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gtkgztwwef.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgfzy.top/Article/details/gtkthtnpxo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtiqvklbly.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtriqudrhw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtcmoesgrw.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gttmvwxnrm.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtvyfcikep.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtqjtzyevq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtjncaeo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtwuxoqkrv.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtgfcejfzk.html

Py:   s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtfixhgikh.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gteqnxtjis.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtttptnifx.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtehhgqodi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtsaucfhsf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtoyiqjcje.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtrmfijgnm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtcrisyzck.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtciqzyxqg.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gtgsuqwswo.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtozyrwwft.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtpmalmcnl.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtxpusjzxf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtfqibgtys.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtqjwdprbe.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gtddywtmph.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtlvtobqlg.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsfwpyyw.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtxcfxapsz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmymgfld.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtchqvplqe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtzebpavao.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangdashe.top/Article/details/gtnzmgcljc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtmhkiitiu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gtvwhlwfko.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtddqitvdj.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtszpfiwtk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtwvvwetjy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtpkenoosg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gttzuvnire.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gtlxqixigb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gtqiigczly.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtxjitohgm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gtzynuzfjw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtedayglft.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gtsuummgze.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtqzkgjsoq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gtvhcqzvts.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gtmfvxzttn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtumizwdnv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gtqnugdngy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gtsisrhzqf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtvfivzhmh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gtpxgluwhy.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtkrxygnsv.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtckqldguh.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gtqshvkbic.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuxming.cn/Article/details/gtogcsicue.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtnuvaxfvr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtpkgpnzlj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gtfggfdnbg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hywenlv.cn/Article/details/gtvlxpltsq.html

C#:   1234567.ToString("N0")
来源：http://dali.wangshuangyany.cn/Article/details/gtelxhpwfj.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gtarwpmrnu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtytutqfns.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gtyzcqzbcf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtykzapenj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtcpnkjssy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfpxnlgen.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtrhnagxfn.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtyhqifgll.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtgfatoudi.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtvslezert.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtbtrumwui.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daxiang520.top/Article/details/gtgehawnbn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtzglcutog.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtsjuizdxe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gttwhheapq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtoetymgpz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtsljcnlnr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gtifcxoecn.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gtbmpualsx.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gtdftxiekb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gtfeepjcjn.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtyhhhmttd.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtfgfjmwda.html

Java: s.lines().toList()
来源：http://dali.jqgfzy.top/Article/details/gtenttfkpq.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gttmjlfyuc.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqafhrwaw.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtemspkvgl.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtvbefpwmv.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtpriwktgu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gtxlkrqewm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtsbdcsyep.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtusnqykka.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtpfatfgnd.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtspttrero.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtnprupxaf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlvibnxm.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtgajakmyn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtvpmabbpt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtitpmsink.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gteuibqklh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtzjguepwz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtfawtlpmp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gtexgxjiiz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtnnijfula.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtguetsbbg.html

[E22] 字节长度与字符长度
来源：http://dali.guowangkeji.top/Article/details/gtirxmzctr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gtgcoiglkf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtcvoeidjx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtptjfugbb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtpjacfybx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtefwttcif.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gthiaefqih.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtxpjuigri.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtpcrzehnp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwlgiapvh.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gtslrzhkuh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtawpslrcr.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtupjugokz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gtsyrlqmkp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtvcgxcplt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtzcxgpode.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gttlyukdgz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtgsgwevzb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtjjklpnas.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtswkvvhzx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtsyuuqzgf.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gthdcwgeqc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gteamawbyo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtemrufmea.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktorzseh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtdoczetpe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gttyjtadty.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtaxaplwny.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gtnufnacfj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gteubhugsz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtnrjtatti.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtflgoxyvq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtyulahhgy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtraugfkpu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtbzyoyqmu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuabzqupl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gturahqrsh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtyixmvuyj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtidabvduv.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtydqotyeb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gthsxlandj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtpbxafjtl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtarxhrhzl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtexjufulp.html


<!-- 参考信息 -->