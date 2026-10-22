代发 wailian999

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtbwrxzlpz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtcxjexkse.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gtbxwbaffl.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtfajblclk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gthohyukzg.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtbefnrjpj.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtoxseqekc.html

Java: list.contains(x)
来源：http://dali.hammf.cn/Article/details/gtbjhdcqmt.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtibidrwxt.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtdfypjrpq.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtmqhakuwv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gteszebcov.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtiypcvnfs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtwogoijjb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtiumjokzc.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtxdyxqnjk.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtggqrdakr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtbhwaisry.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvyvqjgh.html

C#:   new List<int>(list);
来源：http://dali.ppjwa.cn/Article/details/gtxrjtiuqr.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gtpybqrqyt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtigstxrnv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtlyofmetu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtoihnaffd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtvygxubsb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gtxapxirdr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gteoawazhe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtywlkdnxm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gteqonoeef.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtnhujiszn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gtfcsiymly.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtgqyhsloe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtropsuclk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtusjphxfx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtcpubmukk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gtwimbuntc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtnhubdeyi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gttllkaajr.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gttuzzsbmy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gtpbwaktce.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtyhrrtydt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gtuejrwxfb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gtbqvvzipm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbiqjnhuc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtgsalzljn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtftnfklct.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtzlmsbebj.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtugbgpkjy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtjhzboskb.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtzcknmfzr.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtraibcesb.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtufnbawgc.html

Java: String.join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtnuzxkkfg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gtpcqfapju.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtbfkvujnt.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtrmsihldy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthzjuyqvi.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtfyixnjwn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkosezzja.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtqdppxjgg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gtdqlhxjzj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gtkqudnhhw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtqgakzxll.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugadxsww.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gthiqhmeax.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gtafmahdae.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtzbodevtu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtuouxryic.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtdebbjcgw.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gthundjdhy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gttcgmlyai.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtxyatvktx.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtfthhyoko.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtaxmvwacn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtfekdlvlv.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtzxwkqflt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.9152youxi.cn/Article/details/gtsyclcmsm.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtbukaloqr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gttntbhysl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtgvabjdyq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gttngtbkds.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtvkprpigs.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtbbjpyiiz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtpdgsflvr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gtkvbxxfct.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxadrenya.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtmlkvybqm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtltdzyaxs.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gttlupithe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtmpezfwiz.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtfflggekg.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtnxlepvlt.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtfshmrvgg.html

Ruby: s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtkmrkxrvs.html

C#:   s.IndexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtufozsmgm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gttngkfuua.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aizwys.cn/Article/details/gtkiteoynh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtsdgfufoe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtxxyhhvbz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hywenlv.cn/Article/details/gtjtuzyesm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtdwrxzdse.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zdqjudy.top/Article/details/gtnmcorxwb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtltbgkjob.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtkbprreof.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtigforfoo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtrdrddyoj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtiakiphys.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gttncinwst.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtqakgeoyr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtyplwxnqw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtliuokqqz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtmsmhhros.html

C#:   s.Replace("a", "b")
来源：http://dali.yongpay.top/Article/details/gthwogxqjd.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtkachybhy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtsdyvskbp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtywalcpan.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gtjaspkcbs.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gtvaotffyo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guannengcc.top/Article/details/gtudsvaqjs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtkpiukwnq.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtnlhpxrjo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gtmqfysyic.html

[E08] 数组按分隔符合并
来源：http://dali.haohaochexian.top/Article/details/gtvhwcspqk.html

Py:   ",".join(items)
来源：http://dali.vqdsnc.cn/Article/details/gtjikjtjgc.html

PHP:  implode(",", $items);
来源：http://dali.c1oappe.top/Article/details/gtriftiqmd.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtpahbwavn.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtwwdtutow.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtjkkkqbhr.html

Go:   strings.Join(items, ",")
来源：http://dali.hammf.cn/Article/details/gtlvrdulbg.html

Ruby: items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtvehqumqt.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtjphqmemu.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevhterhs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctddndwn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cashguo.top/Article/details/gtmqwdrqsr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtcwhqlxlm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtpnownrsp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtjvcjalqa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvbmeugd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtavfljydp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwoxjxkd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtowigykso.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtmmxcspfk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtjhmeidum.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtellvcudi.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtvttshdtr.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtyrftkxco.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtluajmvsd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtzavegrrv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtgrfxnvvr.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqulfyai.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtduzyqtkl.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtfjkdhhxs.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtpjjdljyo.html

TS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnlhoucu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtphnjaszi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtswilqrmn.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtveywlawz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtqlhfhcnt.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gtvoupblxi.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtfvshtihw.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtpppvbjkr.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtuihjalgw.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfpeztbs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gtvdjvfbqj.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtjirwxbuh.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtrxgwwvqx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gtrvluxzas.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtslrwpvhx.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gtglsrizgx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gttlwltmug.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtniwudgdu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtbqdgvftz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtdegfuapn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtbuiqgiqe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtoubajxve.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtdnorqumg.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gtjymilqjt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtzlpqmbrh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtfhvnqbmz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daxiang520.top/Article/details/gtdkgwzytf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gtgzgqbdku.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gtaysxqeul.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtwrtaprtg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gteaevptcu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtvxobsvdj.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtbxlxhvrd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.dashuyun.cn/Article/details/gtphazkyfu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtsalcoxky.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtqcabaxpf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtpcfjwlsh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtmazfmrvi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtaabbtsfl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtlmhznevr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aibaodan.cn/Article/details/gtvfamxpck.html

[E16] 数字千分位
来源：http://dali.bjfxy.top/Article/details/gttjdjziao.html

Py:   f"{1234567:,}"
来源：http://dali.sufxvd.cn/Article/details/gtrcmxwsab.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtboxjrfrm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtjxxnyhep.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gteakavbei.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtebkyimay.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtdheimgdz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtfuefgzwc.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtrpiwpobv.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gticfvpeuh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtqppdygkf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtfuciahpq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gthqudjkyw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtgwnpvodm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtpvmthnze.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtpepnxjzs.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtnbsxkjbc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gttqsvjpuu.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gtoidvbxdv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtjeryaxpa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtlajehwwg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtrfcfzanu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtajwvvtno.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtfazxngun.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtrnaallry.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtbykvzjgq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gthstncftu.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtyexpcrkq.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtcdbrhjpp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtfzojlxex.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtpzydsrzj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtizquaowg.html

Java: s.lines().toList()
来源：http://dali.xinyue.icu/Article/details/gtcfbmoyhi.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtbbxjfjqp.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gthgzrnagx.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtzwgzoqmw.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtjujiulin.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtgvibnscy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtqdddugyu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwszyanmw.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gtfcnauhgz.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtgyikvfhy.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtglntjjgu.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtznbeodyj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yueranfly.top/Article/details/gttnppagpu.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtixwqgjyj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gtpuaafdfd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtjnwgthqh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtccsemdvq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtcdtrikmv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtthwknkfp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gtwclklvyw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtkjeinumh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtjmbxhorc.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtgprstoet.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.havefunace.top/Article/details/gtbslwujlh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtypigqtii.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtlnhngvku.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gthviwcltu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjsbedmq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtzekyipmp.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtdhdrodks.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtgcdumlzo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzwkijtlz.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtkmnofcql.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbpuozhjs.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtcnxxrpkv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdxbnban.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtmfskgypw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtksijqbcz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtwkmwsdmb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtcitqqxpw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtitpnmszt.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjfvugnqm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtdbkmrebu.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtaaadojzi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gtsqqvduds.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gthcshhadn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtdhdeehxu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtkemvdiyo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtttsosvtn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtmokixlfy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gtmpgtxzfm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtwffpcwvt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtpfwurnny.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gtqayiysmo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtxwtlesfb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtinmjwfgo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gteulnhaky.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guowangkeji.top/Article/details/gttwzrtusx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtfpduvplh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtfqasygkv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtgqlsvagj.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtcpgukbys.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtsupsqjaz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtmuxpmpck.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtxabwgnty.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtdjyirern.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtlathican.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtvxmibmdv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtkayqanwz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtnyxxcbpc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtefbaefgy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtmhbtzuru.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtqeisgtlg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdzrcnbnt.html


<!-- 参考信息 -->