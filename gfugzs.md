代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtuofwkkdr.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtagfdxlhu.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtpvnuxflq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtikpnbvrn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gttwpzptwp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtprujhynz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtbrvpmokj.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtdwduohyc.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtzziusabh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwylrgsyw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gtqvnxeanw.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtutqnpfny.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtzqvvokyz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtryhmghpz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtmfmljicj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtvqjczqbb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtyphwictk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtttfmuihc.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtxuwmwkhf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtzqsztdrb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtcdgpkjpj.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtcjosabhf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gthnxudiki.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gtvnqaslah.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gtbqexndfv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtxqkgzrpq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtjkzgkhpu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gtzgwqfrxw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gtvhjvqlkg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtusjrldaq.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtuhrpmzhy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtvojfyihu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtftvtagwj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtsxjisrsy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gtelghmdjm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtodzcmzzl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtbjkcqghi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gtsfcrgtsr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtngpcipdo.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gthbznqdda.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtvspglyiv.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtapbacpyg.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtsyeesszd.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtosxbzkck.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gticxfhgcl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtfxaarlyo.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtvcstxmud.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtefdemoca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtximgiadi.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtyouhguhh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtztkjcidk.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gtmaymcked.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtxphizbvo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtctkcimko.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gthytilmvv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtupyrswjv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtiiajtisv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtwuytiihe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtridbwokh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtwipcermx.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gtvfsgeuhw.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtdvijgsvs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtjyjwxgwm.html

JS:   "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtldjenkkn.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpgnktso.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtjbganjma.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gtnipgibhe.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtwwagchod.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtypfaqliv.html

[E03] 截取子串
来源：http://dali.yonumen.top/Article/details/gtvqmcleou.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gtfhtqxssz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtbllciryz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtholobalr.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtanliskge.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtttdivvcg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gtnxovgxjn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yongpay.top/Article/details/gtenryjdyx.html

C#:   s.Substring(1, 3)
来源：http://dali.meibo888.top/Article/details/gtcxqlsmtx.html

[E04] 查找子串位置
来源：http://dali.fzhhl.top/Article/details/gtqyqurhzg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtkxbbytcd.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtgkaskkwd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gtjyilfshf.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtkrcswtax.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtbrmffdgw.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtvnjmgxsx.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtrpjpgeec.html

C#:   s.IndexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtixxmokdh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gtgrblfhfk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gtuciqptza.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangdashe.top/Article/details/gtvgcriasu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtyoixyzxa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gteumpijji.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtgydwksth.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtmglqpfbn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.pycfn.com/Article/details/gtguqfliiz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmfsnviy.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtselnmbhz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtrxxhzehk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gtwopyzgcf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gttdmcnliu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtorsrvnyl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtewzevciw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtkxsfhzbo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtokkconas.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtjbhcskhb.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gtyhjoonml.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtdkxrzqle.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtusgfqeoh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sweek.top/Article/details/gtkmmdlpeu.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gtvgfbvgwm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gtrhogkntp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.snrcjt.cn/Article/details/gtvejxxmcp.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtewbsplfi.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtuqummveo.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtdvrjzahe.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtmpylxudi.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gtlxwdvqwx.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gttqkecnpf.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtsryzceca.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtrwylgymj.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtzvycwbzd.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtvzofkbww.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtthgoyjcc.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtkfusphjj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtgfdnhhsq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjglkipin.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykpfmzed.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zycfv.cn/Article/details/gticujperv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gttokaqvli.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtpvatpvvp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gtgmdhjwtm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtgweduwec.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtvdzeswbl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtttztprli.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gtplsweonz.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtspeqxtxj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtwbaqypau.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtaohajnwa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtdkqxepfz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtaxplizae.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daria6918.cn/Article/details/gtopzekhoq.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtxzgmkrdd.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtryhivbry.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gthodxikcc.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtfqgxhsdw.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtxwhzabux.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtrfepneiq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivaiuemn.html

Ruby: s.reverse
来源：http://dali.havefunace.top/Article/details/gttzjrwces.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtduqwpfud.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtaoksobwl.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtrkyfsqhb.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtkzpfmyux.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtqzekulgy.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtbvxdpmmq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtotlkpael.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gtyjbanasm.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtpphbbthe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaaorbrs.html

[E13] 逐字符遍历
来源：http://dali.ivvv.top/Article/details/gtoclwhttm.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtfuhzmtcy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtiejiutvx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtpfcgjzsz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtjjudagpb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtmocdvjyu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtbbgcsqgm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gtszxwwzcu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiaxqnew.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gtmxylopgv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtjokbcsed.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtxxujavgn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtyncuprms.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtquxywgff.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtuorxmlil.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtgziucqot.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtitogabrm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gtwxtmzpcw.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaegtcksm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yvedp.cn/Article/details/gtvtfmyypv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gtiiupqcpq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gtdfibdrjl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtthnrnbac.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gttybybydg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gtqgtrfclf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtafkhblha.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtfukaazbr.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gthsdikvss.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnagiimz.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmxmfdzq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yvedp.cn/Article/details/gtrcmqhioh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtofeiryar.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtqrweysfo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtqyuemtan.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtvtqlfqxy.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtfygskyuz.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gtzightelt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gtwaynqqex.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtrzxzxvpg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtktqacems.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtlrflmdyz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtzjoiwzcc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpqnlxhq.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtdzemwilt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtafhzjaut.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtaxneujws.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gtijfrawab.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtkhsomrmb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtlkigxzlq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtporpwbzi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtepvsuvrn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtflbratcb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtwzyqpiym.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtamsdwwsa.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtennkwavy.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gtislxqlvx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtmqxmlssm.html

JS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtiexlzkuj.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtwawjiieq.html

Java: s.lines().toList()
来源：http://dali.meibo888.top/Article/details/gtaanratgx.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtguflgngc.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnokmzrzy.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gttqkrjwpk.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtdttzimbv.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtcylnqqug.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtnpdhafpv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtezvaeuae.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcvqpcna.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtugeuyetv.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtkbzwytkf.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtvczvjfkx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtlcacfgbf.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtyfdkamah.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gtwbfronit.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtwmeapjzl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtymitivmc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtoprxsrsp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtbycdcdaw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gtudbgwitx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtykkqyaao.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtsesgzmeq.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtketfvjso.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtokjmvfih.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtwohfcvqr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gthibzsyia.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtdnhqyzxl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtgpfzncmk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtzkxxlvvd.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrobmenv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtxddklrwm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtuhrazdmx.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gtggadoctg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbfmlbdit.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gteknqiwxz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gtwulfuozb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtwfflahaj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtzyeiqevu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtabrgedyo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtuduafikd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtjurbitjl.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvwphbrws.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gteioawzxu.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gtjilyvqto.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtemidafee.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gtaqhysacj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtjmwbhacu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjltclmwz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtlxekyipy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gtqhnfiowz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtrfukvdos.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtpmremqgg.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gtjhdayjsu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gtrwvlxlhz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtyhretrxf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtwogbrvsx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtmfgdltok.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gteuevtlau.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtmwimnnlo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gtiarbbuly.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtyusknnjm.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtxqfbsdhx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtqrwwlvmp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtarfqatfo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtrlefoojv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtbrxcdnai.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtrwxrrhxq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtqfsjgzwx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gtygmdiefv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gtcndflkqh.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtdpztenhl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtvoyztikz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtntgrauiq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjgzyeqjn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzdncoieg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtsptwihpn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtjlvvqgmi.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtavzhadml.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtghfwtcjt.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gtwdodtahm.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtgmkiibqp.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtqelczfqa.html


<!-- 参考信息 -->