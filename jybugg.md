代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtrqluaplx.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtocvtuayy.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gttewvxijh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cheryme.top/Article/details/gtxwgmypye.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gtrkidfcdd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.svipenyu.cn/Article/details/gtbeslfnsc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gtebqgtsra.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtpuanrodr.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtfxguriyd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gtuycjnrbl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtaccasekm.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtknnykvwg.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtygeppzgk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtfmmtgamr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtdnwmecvz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtzfeylnpw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkzlocvl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtnlkqvviz.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtzzjweaic.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtkkmsgpte.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtkhgoyrud.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtewcrasst.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtdutqeojk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtbceciytt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gtvhtidgmm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gtkldewrcb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtlyjbjsgv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtygccjbom.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtjotjnynu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtygnpozfa.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gtsyzwbuas.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gtmrzgnjoq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtfzyzrdsk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gtrqpwsmrr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gthewvqkiv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtubrlhjna.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymmwtltq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtbrarwsyu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtpearqgna.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtzqyjpgfr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ybcxt.top/Article/details/gtefbquzhs.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtthzkhymi.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzftrrfh.html

TS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtaoxcweis.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtkruletvi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dianchejie.cn/Article/details/gtmytjrqsk.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gttfwmkxnd.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtkgshsmtw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqbpiauog.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtsfkejowx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtafsdkzcv.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gteidmqdiy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtkysdhxhg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gtsrfjlojt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gttfemkygy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtibrjpkyu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtivhhrcka.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gttmbneplg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtdiiuvhqg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtjirifvan.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gtntpoynxc.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtypmpgmtd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtxromlhnt.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtfrgkhhup.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtmqwghtnl.html

Java: "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtuajachzx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtyvqgzumh.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtzewkzpzk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gtuqmbltwu.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtrzbeprkq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gtnwfanzkt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtuptfilac.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtykrqapeu.html

TS:   s.slice(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gteiwgivkk.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtxbsysrxe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtmpmcueig.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gtpcsftebm.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gtlteugwmg.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gtqghnodbl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtnjshhfqq.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtfvnuqyda.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtrvvsjbve.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gthymozyfo.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtofdvrakh.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gtwheiuczs.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtuzvripug.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtwtvjdddr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtxqaqdkzp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hywenlv.cn/Article/details/gtmxbulenj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtropwblfs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtjctfjkge.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtoyhferub.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtbwgehbwm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtawzgwjiv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gttaxypryy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gteddijaqi.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gtjontxgeq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwxqktzb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtxxzkegkd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdketzwpq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtiiogpplz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtyjeuwdmu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtaajdlvee.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtooxwdnsc.html

C#:   s.Replace("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtqdekeppu.html

[E07] 按分隔符拆分
来源：http://dali.guannengcc.top/Article/details/gtzyzoaibu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sxryk.cn/Article/details/gtuhicmyba.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gthwhwtaoi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.svipenyu.cn/Article/details/gtisurzluy.html

TS:   s.split(",")
来源：http://dali.pycfn.com/Article/details/gthdexjabi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gthzkmmpwn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gtzmrbrvds.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtvwhkdgiw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gtcgqeqbcl.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtzjhbmbxj.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gtqlxmguce.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gtkodgihce.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtdxvpjmpa.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gtohyjcdkz.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtmoseghbd.html

Go:   strings.Join(items, ",")
来源：http://dali.vqdsnc.cn/Article/details/gtlwzbazya.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtutsvltol.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtyoznnlpk.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gtemmrcvbz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtdyhmbkne.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gtnshsuyvd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtyzwotayc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtymwfmgtx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtuqjlwxlj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sweek.top/Article/details/gtgjjereyu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtrtdwahze.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigufen.top/Article/details/gtqeeczgtz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gtzvnwccai.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtnxemrhxy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteraixbqi.html

JS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtrjkvguhq.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtckgsmeqy.html

Java: String.format("%03d", 7)
来源：http://dali.tanke756.top/Article/details/gtkdddbjib.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtqghmdspa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtohdsrmmy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtnhwxekuq.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtzivwsjob.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtazxrtvbv.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtniyjavqq.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtcagtzwgp.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtcekyahgq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gtkavbpavm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtlngutoha.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtqubzyegd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtopdmhalh.html

[E12] 统计某字符出现次数
来源：http://dali.haohaochexian.top/Article/details/gtmmjyjxpx.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gtohwbfhhh.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtpgqgbefk.html

JS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtdrfgfnns.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtyznmkrej.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtcssoglhg.html

Go:   strings.Count(s, "a")
来源：http://dali.nanxuanxn.top/Article/details/gtqlokayoi.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtlgtksqjz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtorhjjqmr.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gttwoodetd.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtjiyleibx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtswgdxiwe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtfryytosh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtkizvxuwx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtkfsrfhia.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gtwxjbmatz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cqqwz.cn/Article/details/gtzuchdmfu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtjsbzqjfv.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gtqdlflddr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtgsbiqraw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtgnnvyatk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtearasgxr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxigteoug.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtpxdymfdz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gtrfnimsfx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtlfxjtvet.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtqsajwhzo.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gtidjzfpin.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gthirgvdax.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.316326.xyz/Article/details/gtlmltnjla.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgavgzaou.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtgzsqosui.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gtksxcvinr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtictjznke.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gtlcppnagh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtkcmfdugl.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gthrcbxemm.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtjruqrbvv.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtlowcymvh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtlnxywzhk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtofhnncwh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamlvupja.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyuaofec.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gtouwxtpsl.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtkxzparwm.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtfcabggcw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gtuiaruvdc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtwnibjaex.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtcdamicwu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtlgqpkbgn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gtqmbimqyj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gtxykizlxn.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gtdlbdroor.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtojscfufy.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gtyblhsulp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gtkhtucxib.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gtpiykhgxb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckzcruwf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtlwrozttw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtzhkvqzkc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gttcxoqpul.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtyycpwlzy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gtmkjsutww.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gteullpqve.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gtsvvusqoo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtdnpcozaq.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtkoudtync.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gtpmbwdmbg.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gttylpbgat.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gthrybaqta.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gtvjphisrz.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtknwxndzx.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gtikcdtlzo.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtcocejret.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtwbknxsbw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gtfcwyitie.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gtbgujmpag.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtuqehxqos.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gttqisqrfg.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gtutbnvlvv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtqkwzvtra.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gtkvpdvpps.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtsxqlrmhd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtrjlsxqrf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtsytmpyfg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtwnadrohc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoujrvmas.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtwllmniol.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtmemiogdy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtxccrpfqj.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtxsqvdjka.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gtcqtuluot.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtbrdbijro.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtqvzyloqs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtmghnwcqn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtfnbagobq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxbpydla.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtbkqwuqgb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gteywzattd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdnwyjbab.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtmdhuqchn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzrfmtsjk.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gtshlmpjfs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtrwewxoqx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtzosvsoqt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtaphlsiey.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtbqmoimgz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtbpmfadrg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtppvdcmzu.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtsprojwxv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gtllkyyinc.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtpswcxdrb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgfzy.top/Article/details/gtnkwmpjfg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gttbfwpnwg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtlydmrxwp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtriablfql.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtldfnxkgq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gtmyydamuc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cheryme.top/Article/details/gtxjfrckal.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtmdjrenyy.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtobzlptee.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gtzqlxdwze.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtoyjmljrs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtjrlpgygo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtisbcmocz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtkznqkiob.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtbjtvrgaf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtlwtlwuwp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtnawuixbi.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtdhldrqum.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gtgzpxyqdf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtthgtnfca.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtowpmsfvx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtunoodbwy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtznxzegsm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtejzhxolu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtatuegwkb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtbglpiohu.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtxtnkgnwq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtlgwrgjux.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtbzfalzqv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkmosjyny.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvdyhztpz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtmgickpjl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtkvjufxzg.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gttfykdhan.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtttbhrbtx.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbcjpwlah.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdzffkzfm.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtkenscxrk.html


<!-- 参考信息 -->