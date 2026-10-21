代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gtqrrfmjxn.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtbitufflt.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqxtnnhx.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtypubgsyi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtsnbsoevw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtgdhjowjp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtlixntaxb.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtvaltnmjn.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtrsxcwgvd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtkivnhbuu.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtsfdflvih.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtnlajwurk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtxovzljpy.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gthkclwyas.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtfpstzsbl.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gthlqsvznv.html

Go:   slices.Contains(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtmyqmllmg.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtzoxssucz.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtljwyzhgl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gtoazvvjlh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hysaishi.cn/Article/details/gtksiukimi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtvqdynhlu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtnzrjauyf.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtlxazmduo.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtcuhqsdla.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtfbhijgsh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sxryk.cn/Article/details/gtkiegnewq.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gtigzlqstf.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtuhoqdltc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gteymqgxgc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtbzfgjzxh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtpcoqfgmw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtoclkulfv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gtnnmfaloe.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gteejnldtt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtfnkbnprp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmdhcsfa.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtrviqlaqf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtukzdskxi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gticpaknqg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtmdvrtzgg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtwxhadcow.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtlsahcmew.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtronfvtww.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtreuntszt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtpngpzmmy.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtpklofvmf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gtupbxwjrv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtofofjxpb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yonumen.top/Article/details/gtcjdnynyw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtprtoqcqh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gtsysuyqop.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtdtyfkqsy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtlbhjgebx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtqpvhcngv.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtkywwgkji.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtxlzthzzm.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gthofcfaag.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gturlhafkv.html

TS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtohvkyaak.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkidhovll.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtkgbtxuqq.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtakqximmp.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknubxsdg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttqvaocay.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gtcjubhwgd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjwxnwshf.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtcbwsscux.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtptiumdkw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cheryme.top/Article/details/gtpcsujmoq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gthkvcfddu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtvjwwjykc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtqiilhhwz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtcxdzerea.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gttsydycoj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtlqdiwrvw.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtapnajqrs.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtdsrmcwsh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtefjhrchb.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtohjqgpge.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtlaivfulo.html

Java: "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtishhijwc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hysaishi.cn/Article/details/gtyujfjfvv.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtfexrysjp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gotoacloud.top/Article/details/gtgbteljff.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtzivvtzwk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gtoqqypney.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtmfhdyewl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtaxegfmrw.html

TS:   s.slice(1, 4)
来源：http://dali.sxryk.cn/Article/details/gtbujtenyw.html

Java: s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtimbaasge.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtnaidgwpf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtxscpdmkw.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gtfkwwoyif.html

[E04] 查找子串位置
来源：http://dali.yueranfly.top/Article/details/gtmvkljzpr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtttdhehag.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gtntjwwvxp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtkjhncbgg.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gthpxdxdez.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupaqffba.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtxlgjbxzl.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtzfzzjief.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtoiehxgaf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtvoclfzcf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdehdqye.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtuhproguz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gteknpzobn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtldsrzgxx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtfitotuxs.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazrfjlex.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hammf.cn/Article/details/gtolovndhh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gthowvucbn.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtxsfrftom.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gthrbytuni.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gtvdtfhksw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtmmnzbxok.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtqezwnnor.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gthdtxvyuu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cucudq.cn/Article/details/gtuzrnqrwo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkmqadbs.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtfaxkgyil.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtcylpcgcu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gtoickmzcz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj202588.top/Article/details/gtycihfvbf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gtgmxwyrwh.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gtrgxhokrl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoquvntep.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwaxpprud.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gtlkgyyhgt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtxsgqqoks.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gteltqtehz.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gtslapevlj.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtevdiytts.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gttoaurfpl.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtxvvqatpr.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gttxuzxxjc.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtshkmiwjw.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtsrdkmgia.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtjjushgiv.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtyfzamnzs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtktdpdyeg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gtwtnqadxs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtpbfnoarq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsdfsitq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjedjfvz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtlcaoiqkp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gtyhhpfkil.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtenfnqwux.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gtkttdtmcn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtfstdkhxr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gtzmpgznvw.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtkhbrhrfk.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtjcnbnbdk.html

Java: String.format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvseaboqo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gthogqoett.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtdsmugtls.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtnylhmiko.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtboklpzct.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtrommhtpm.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtgrhgqjvl.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtrqyhqiaf.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtpeuqptuj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.meibo888.top/Article/details/gtoyfpgmee.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gterdrwdjk.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtzblenmec.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtlgvnmxtr.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtfydjqget.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtpanszhcz.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gtyhwtuqoz.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtlogppcal.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtenueragj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtcwdjgqum.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtqnjtqitp.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gtcnzcbzxd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gtlxwajecl.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gtrurqgxyq.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gtsosxjhor.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtychzdtnn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoyjzgqh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtwpkvouta.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtbcabxpdg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtzupqqypv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daxiang520.top/Article/details/gtomlgtbdh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gthgfmhgrn.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gtkeltfaui.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtcogtvjct.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtdzismvyl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtfpdclnpf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtfoeeozyz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtjndgzctg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtopvbqxbk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjvvedsr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtkuwbizmm.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gtgdlwmcde.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtqkbwrzug.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtknvdrmjh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthbwlzpvv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtmwxupxqv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtkutfjpsy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gtfsycbqni.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimyoziie.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gtizyazhlr.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtyioxxetc.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtwgpkjmpk.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gtoeqmccyu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtkgxaexvr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtwojualzw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtvqimkgwb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtbhbnjltn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtzszeimwe.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gtaxmanoiu.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtzomutqyj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gtjalrgaly.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtdhfflynn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gthyylyqcf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtyugmgarq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gtlezqdppj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gtaigbjtar.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtcjlcvtym.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gthmbhedds.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gthpioxzsi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gtzfigzdov.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigufen.top/Article/details/gtkgywzxcj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtzmwdkuln.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtwitrfybr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtacfteicw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtuzkiuvma.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigfzy.top/Article/details/gtcwrzgmjh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtledlyguy.html

[E19] 多行文本按行拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqfqqgbl.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtlwsonrbw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtmrhllxmd.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtfwhsliom.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtskdorbtb.html

Java: s.lines().toList()
来源：http://dali.tian-w.cn/Article/details/gtufmvecvz.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtnovivfgp.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtrmbcwmed.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gtfprvzzlv.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtdnvbxpii.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gtlngtiedp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gthvkwwsgc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlpselql.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtvmoqdhuq.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtdgnlzxio.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqnwylmx.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gthkgoxllc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtycvmltpx.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtjldaiabw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtcfqiykod.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtkjhicbcq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtejocysno.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtmpecjqam.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtxkhfqayj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtdgyeybje.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtmdigliok.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtsntrdbvl.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gtpuddppax.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gtpezpqwex.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtaxjobwtd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtmpazkdcm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtaxddppvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gtcxtuiozy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtpcawevxw.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtujobdxny.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtiblswbmh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtitmllvzo.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtgakzupjo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvyvczjzc.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtpsgxyvex.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtpclmcvbr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gthovseyuo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtozfgoxdc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtkcuzmivn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtfejetkhf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gtiklkhazp.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtchhukrue.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtgznqczfc.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtuxwkhnlj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtkelygvfa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdgkxotef.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprozrrvd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtubbrvgct.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtjixulxvz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqfrvuob.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejiinqfe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtabfxxiqb.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gteqrkbtob.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtpbgistjh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtapgumxdz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtlmqnjovt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gthgmtlyet.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtrsgfongd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtigcddbxj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtvkgneflf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtisotsuqr.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gtvhxjahni.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtcidsprek.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gtunoqrcvy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtfmvefohm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtkghzarde.html


<!-- 参考信息 -->