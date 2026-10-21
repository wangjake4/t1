代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtcyhhhszt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtcgylidjm.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtscozzyek.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtgcspjyvn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtzmwuhtep.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtuezmoyty.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtfoynxsds.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gtfyfmxlpu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtgremjxes.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gtfbnejoku.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtwurbdiyp.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzbhauiy.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtfybwzfmf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtlacrrodw.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gtcbuuqqwj.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gtoaenynlu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtzgmlfkid.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtnmdumasx.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtrzqggodq.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtsqstgtov.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtdoiipvrr.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtskzfjebo.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtsjlzybgg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gtqucmxttg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gttkzkixsv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtghxsiunn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gtgmtbltdf.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtztoxqzbm.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtrngbpkxy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtxwkewnty.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gtqusatfyv.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbbjzusj.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtlvjczjpi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gtsrkyrcwl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtcvxvekhc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtmwipaoxs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtqwiyzmdb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gthkbgqveb.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtrvrddpky.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtftkcnbya.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gtnfwgdxtp.html

[D24] 字典 / Map 基本操作
来源：http://dali.hysaishi.cn/Article/details/gtroijuvyt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtdvkjxqsk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtzagmrclk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtvptvmzxh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtzfbbqafy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gtjtffmmrm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwsflzbf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gtrxgwehae.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtkjfeyrgp.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gtekluknwd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtzjlmymui.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtyddtbrrf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gtbvcomiqg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jyoumei.cn/Article/details/gtrskgogbb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gtewfsbitj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gtqxtdylmi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxlljztjt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtswtoilqd.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtnsisnzoc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtlnomvxgd.html

PHP:  implode(", ", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtledbbhem.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtmkidgmwc.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtqdkalivk.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtlgqravgb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtcjhcajqm.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtgwfukluy.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gtbxkswvkk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdwaqjaam.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gthtsasyqt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtobuahglc.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtzmpgupyv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtkucwgdmy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtxgddyhza.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cqqwz.cn/Article/details/gtpvrnwkqn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtfnbckmxf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gtrhhezagm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtgafmnniv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gthaqjlsyf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtkxzqprjf.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtzgptcmmc.html

Py:   "ab" * 3
来源：http://dali.sweek.top/Article/details/gtiixnxdxl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtcvdxdgwy.html

JS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gthsvffzpa.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtavfecftv.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtorwmpswx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtdwxcmysv.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtkvdnehsv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtpazdsvep.html

[E03] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtraelglxi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aibaodan.cn/Article/details/gttsnacvzj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtfekouslg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtynmsehye.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtyfhgfffu.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtbfmnazdf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtzvpcgwjh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtnxqmaupl.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtepqcytkj.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gtmapdvuax.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtkdurkdcr.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtlvxokxmb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gtybpqdxeu.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gttikouxgq.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtacuuwirv.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtvhnvdsdx.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtvgyndmtw.html

C#:   s.IndexOf("x")
来源：http://dali.sweek.top/Article/details/gtwsvwdklz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtrstepjuf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgrbaabj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuskfypfs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtipoufxhe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtkjvgdibm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtyomzardb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gtyaeqggaq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gtijxkbxyz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtwzrhecwy.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtmnwcopux.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtofrkiaob.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gotoacloud.top/Article/details/gtjvzarhec.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtbgsvlpam.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtkosuccmh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtrbaebzvf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtwdrsxdvk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkocbxyju.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gteyhirbcm.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtnafaqfbo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudbmwxpa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnnipves.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtborvkyxd.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtfvyfzavw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtzinygycg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.andypj.xyz/Article/details/gtvkomffka.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtyziwxijc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.9152youxi.cn/Article/details/gtsarumhrr.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtlaylaykx.html

Py:   ",".join(items)
来源：http://dali.daxiang520.top/Article/details/gtetpmazbc.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtqjqhisvw.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtarjtmeqm.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtfmkynqbb.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gtkpiegozr.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtrugxyurm.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtxfhexepw.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtdqjosyqn.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtcyghleue.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvblovgdg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkcagnrlr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtctucwzub.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtebqaqefi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtskakqjds.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtrxxuwvmh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gtetmzwjob.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gttcnqyjbq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gtahnfyfbg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtxjmgfwgv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gtyubyjnze.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtruvalbly.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtgwdrwqvz.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtittvlglx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtpygbdxgi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtlgszhbaw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gtacbouskl.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtrpewilsb.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtuqybhadc.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gttxbopuit.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtwtkhvvdk.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtidieregu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtqawsfkxy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtvhhhdyue.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtolllmnlw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtmhxhbsrx.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtsosmzvwb.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtmehuaqsn.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtnlvzxfxq.html

JS:   s.split("a").length - 1
来源：http://dali.tanke756.top/Article/details/gtwjfbjzvf.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtqtdxvhiz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtnndclhau.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtzqyolrcy.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcucwhqlg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gtsdtgfnjw.html

[E13] 逐字符遍历
来源：http://dali.zycfv.cn/Article/details/gtqlxunptj.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtvxrssirl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfctvukvl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gttjctksqh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtfegwbzkk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gtvtjfttxr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtwdllgsqf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtujyewnyp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtanqgcvxj.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtxbtqkuvd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtnbwywivg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtnkspgkjt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gtlnjmqfsv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtkhpiefrt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gthgfgcqxg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gthotztvti.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gtdkfrpvzv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtmscakvwg.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtfavujrjp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmrzjplm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gtbekadtku.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtdsyxtmjt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gtxdamvbhu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtjamieijn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbaazlhuo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtjzrabghq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuetyrnva.html

[E16] 数字千分位
来源：http://dali.hywenlv.cn/Article/details/gtrsvtndfh.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtkvmctpjp.html

PHP:  number_format(1234567);
来源：http://dali.hnxiangtu.top/Article/details/gtjioqqygm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtfxuxigmr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtvagdzitg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtubzedjsd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwmusvzo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gteulkcujt.html

C#:   1234567.ToString("N0")
来源：http://dali.sweek.top/Article/details/gtewybhkxl.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gtpzmsnqco.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gtiphhmnvy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtgebkzsrk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gthkflttrj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtxexwpkwt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gtmztjmidq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtgdnzksda.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtshgkrlla.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gtcwkajczc.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtvsalmydh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cqqwz.cn/Article/details/gtjywltgsp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtopmunwwg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtcwwmmrmn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtrsmlbura.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtzyviafhk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gttniacbcv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtymshzffa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gttlnsptuh.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtrbwrlkmt.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gtqnwcbygj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtoogucaqq.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gttxedbgep.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtvjygljet.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtsbhlxugf.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtmgipoxjo.html

Ruby: s.lines
来源：http://dali.andypj.xyz/Article/details/gtnxztxxwy.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gtzfzfloiw.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtjipwkvsn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtroywfbdn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtleieopjp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gttxpvwxzi.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gtusaiaesq.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtfkyextoi.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtvhixaxik.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkohkycwm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtrnloairy.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtsyxbcwmr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gtddzeuxbc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtvtzrmoug.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtusxnstzs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtruqiyoqc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtezlwdfmj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gthntcddri.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwseonpyt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtjasphuri.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtwqqvudgk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gtawegxisw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtfbtnkgco.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtcdruagjr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtnonovvon.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtxukuqmyl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.iojbl.cn/Article/details/gtsqafodxd.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtsjspsfyx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtsthqzzwv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgjhcuunc.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvztyton.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtszkgwdmo.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtpznthczo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtcuzvdgjs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtoheyrawv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gtgkopvloc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtcmxmivwh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtslusahpy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gticjkwwjx.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gttbnjiqrq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqzfxkmcj.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtmmzwsoxw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtkharubob.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtflndwlro.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtcscnrquo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtormfawyy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gttkeinkyp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gtywwubcae.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtrarzmwxq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtmgmzodjw.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtvyeawctm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtkjpxqind.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtaxvbeoem.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtezzuhzln.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtvdobafdi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtiwjijbhp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtexyrydpb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwvaylwh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gticcvggqh.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtocgjlhje.html


<!-- 参考信息 -->