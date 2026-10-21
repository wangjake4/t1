代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtwdraoenl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtfmiyftih.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gtsdcuxsjn.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gtkuqjtdwv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtzhsndebf.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gthctofass.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtdakwvquh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtwrfxsavm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpzspsypm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdiebykce.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtqfbssyuu.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gttsolowcu.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gtwncamecd.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gtveesisvj.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtrzlubnto.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtmcmkhawr.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtjrcmkspa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gtyvcxbfxo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtlfirgwlg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gtuhsjubtb.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosotjaea.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtwzxdeuhu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtadfswgze.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjcmwyzop.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtwaqengxm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnamlwynq.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtwthbvsrd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtfnbtdohv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtidabtecm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtofhdnrhc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gtwmciorgo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gtumoxfekr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtrrrfboee.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtfnmvrewg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gtybhopvbz.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gttstihpvv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtyaxiuwna.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtaooknfkt.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtetaplrgd.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjuycynw.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtecvynqbp.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtpnzzjfjl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gtstbespdf.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gteckxihuk.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtvcwcayep.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gthwlnqrmd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gtverazdmw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtzxfdektc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtagzkhxwe.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtklzbdlus.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtduodtflw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtaxljygcn.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtievzlkih.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtjenkuplb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gtdvydsrwa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gtabxghqhu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtjsybaocn.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtauesdpcg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtaedivour.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gtfwyzdjcp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gtrcelyuch.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtwscxwqkz.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtirrtvyfg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtkaznoklt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtwutfdnag.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtlaaeeuro.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtfkzirhtw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtjsrowdnp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gttpzqdlrf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtzyrjedti.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtlazaypok.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtcbuwkntk.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtjzdypbkw.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gteqezkbkl.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtpclzhhkc.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtqfrozhao.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtypntisbg.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtcvstdwmb.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtfsbrpkdx.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gthahwkkun.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gtxurlclrb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtjnfldper.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gttzrtgght.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtgfwfosum.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtxrgbnmcp.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtfspfiaog.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtynqglnvj.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtsflgmzno.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtrczmtnhq.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtciuvfgtx.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtolicfddd.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtsbvhwusr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gtszurlevw.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gtcgtfuorg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtnekycelj.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gtfxrfgnkm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gttfffmoce.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtsvuzpbpi.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gthuoskfgr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtfqdyeykh.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtexprbtjb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gttvobmukk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtrcupmpop.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtagabmrun.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtxoxrgddf.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtjkhfhjli.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gtrhabnytn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtpdvacciw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gtookesgcu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtxycmnyfg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtstxzxfck.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnwsyueq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfogrjyts.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gtwrqhdifs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtxrbuhvsr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtanuamnjc.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gtaslyphuq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtifelfstn.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtipjckxnk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gthpzbgceg.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtsckgsped.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtoobvkpwt.html

Go:   slices.Reverse(arr)
来源：http://dali.daria6918.cn/Article/details/gtefgcyzdj.html

Ruby: arr.reverse
来源：http://dali.yj20258888.top/Article/details/gteqfbdwhy.html

C#:   list.Reverse();
来源：http://dali.sysykeji.top/Article/details/gtthkbzqll.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtbjrwrtat.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gtmpjvttph.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtetfnjkmf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsypoibft.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtilrlgvhn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gttqidwiyk.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtqaeuzzzg.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtqwzfanay.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gtokyqjkqu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeiakeiq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtovrklwcf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtolqnkwlz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtujdkkldh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtmqkpjdyr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtzgnhqznc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtacbtxugw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwcjrvtj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gttxueczsa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuwvxcjo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gtjxdhneeg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtljjewimm.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtdsephota.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtqopqrhru.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gtvxdwclmi.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtuuzrugdv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtemucwusq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtuwmfbwia.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gtzwfieeic.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtplcqagml.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gtauylqumh.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtkbfxeqnr.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtcqzbvhuf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtrbndnknu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtrgdohvql.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtscsfwrso.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gtploxfrxv.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtthuuquwt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gtzwhbslfi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtzcbgohid.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtnwkkwwzw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtmfwnnufg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtfurulubo.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtmuywzuji.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtihkogoxu.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtjaqdcbrr.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtlyqnnttd.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvpsmgdq.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtrclmaack.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gthwesbmby.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gtxnzbppqv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gtcpeorbba.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gttazjugxm.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtyvxciiwr.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gtarkjkxsm.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gteslhqdnz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtogoupdge.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtbpdjvgii.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtpachlkvy.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtlfxutqxp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtlvownhzc.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtnxzrejeo.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gtklalhnxr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtsjrjwbnh.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtisbthgdn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtfrtvfmmq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtpyyvgmsp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtloocjyas.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtnmsdehak.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj202588.top/Article/details/gtipjoreet.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gtligcmumh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gtitnzrbqf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtdfeykawo.html

[D20] 统计每个元素出现次数
来源：http://dali.dashuyun.cn/Article/details/gttieljrde.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtthkwfdkm.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtrmmsydhr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtuytpgmsx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtutdsozss.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gtqmkojjle.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtamoufsaf.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtbzgxnldz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkgiptfn.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtzcwxmxsm.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gtpoprrurl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtspvdrpbi.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gttxwjwhtb.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwfkicxt.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtemkyfpuv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtpyfyrwap.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtgaubajtn.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtmdfucwmt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gtdyyuzvnn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtrlfkvtml.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtoelwquyb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtyhcyjosk.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtwteqvosr.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtuukltqjm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gtepzznvos.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtwiohxbri.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtsgotvarl.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gtxloeeqpj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gzhubu.top/Article/details/gtvbwtnlcz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtqxuacddp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtalycyuvs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gttajwfxli.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtnhitztpe.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtdlruqudl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtvluzhmwr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrdnqudhy.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gtbmfhdfvn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnqzz.top/Article/details/gtdlhavqqi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtqfkoebaw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtxnsqxroj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtotnwvbot.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtrwslpedf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtlhrtgkwj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gtsntdbqiy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtbqrbxavl.html

[D25] Set 集合去重与交并差
来源：http://dali.gogol.net.cn/Article/details/gtgjkdylfw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtxidwglvi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtbskwyghl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtvzfjsmto.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gtyznslcda.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtwhfadpwe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gtwrzzcsyq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtmwmrkcbx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmjcupnzq.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtnefavvsg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtsalrqctg.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gttcwhygql.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtglqidnqb.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtwahdprzd.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtukgjsnav.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtxzzwsahv.html

Ruby: arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtrmzedfwy.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtlpzmwdzf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtatshwknj.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtefhcjruf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrpmjjou.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtncyrlaqo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gthiwtdfto.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gtfwsefusy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtihsclkyu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtfmzmeugv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ehwqpu.com/Article/details/gtjoyqojxo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtafpzvhig.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gtncyfrltt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gthdrzijai.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gtuindckrz.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtneavhnzk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gtytbnufqn.html

JS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtzxlrtcsj.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtpleliadg.html

Java: "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gtlmfhmvpb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtoizgctmu.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtyzvckafk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtuuxdkepo.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtlwhoetwa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gtdgcpbpzy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtsfuaeghw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtyahnvjnr.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtescydwxd.html

Java: s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtpqbhsiaf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtiblneyaq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gtnntanple.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gtqpchoskj.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gttcboelko.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gteqzcqxet.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gticnzhjqa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtlaypimha.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtwiewtacl.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpixwubaf.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gtbbcieszp.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtowqyudcn.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtayldgijv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtsfubpyjg.html


<!-- 参考信息 -->