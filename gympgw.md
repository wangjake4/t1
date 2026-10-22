代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtqvskxcvq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gtjsyfflla.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtshvelxcv.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gtsbsnbxey.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtnwaibtpi.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtrkreakbx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gtrbmqkeja.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gtmhhsewoh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtfoaxcrmd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtotqdpbno.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gtbtstdfrv.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtlmtacivc.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gtqioctbfq.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtkwqlmylp.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtnkqiporc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtcymdweog.html

PHP:  // 无重载
来源：http://dali.yanxiufei.cn/Article/details/gtapzsczwk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gtoywmymxw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtqdsllqqj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtcsyexlvy.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gtxyixihmo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtimvkrhwb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtptrgherf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnmhmhmtp.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gtfjgnqclp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbuhimpq.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtqbkdkuum.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gtkcyopyon.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtfqzrijzm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtickmkrnp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gthgvzaaav.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtevtcutja.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gtvaeppdyr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gtcxlpgbks.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtbsdfztlm.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtlfwntjay.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtzgmpdcfc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gtgpxyuygf.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtskehzmwj.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtidermrrd.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gtdqoucjeg.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gtpchmyicn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtydtutpwk.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtralrjbkm.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtjbqmzoga.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gtivgxzrld.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtwkdynpxb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gteiylkkhz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtzuwphndr.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtjwqtqczf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtqofokgft.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gtcxmxteqf.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtnayltxqg.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtivpgdxtl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtkyrgmzoj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtrfvhtqkc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtwqrmddyc.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gtcsvwjqkg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtlxpgssuq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gtrreutate.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gthstwtfpv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gtdhmlytyz.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gtfhcfmglr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtbfbfndmm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtrchmwfid.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtqoievbkr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gtglswwquf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gtetmrjoqp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapuqnpqs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktdnbpbr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtfgewgafk.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtlbhktlgl.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gturaqxazs.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtyrxyputh.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtwjaxzfqz.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtmlfqgfbn.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gtjrvfuasu.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtnfiyybyw.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtblzwogxh.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtrptorspi.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtcgjqggwm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmtpptoo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtnxcvcddi.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnivfxbiz.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtijwkybrs.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtwvrbhibv.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtoreksmvq.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtnhekwyet.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtonpocxdb.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtsdumnfhh.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdgcwclfj.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtuxmkgklo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gthujjgecp.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtqtyhoyqt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtwrdljlwz.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtyjfqmfro.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtwtwyqqfv.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gtkznpztqc.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtywzqjvya.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtmeuwlfzi.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtxjbmavao.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtuulmadkv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gtmtdhrdko.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtcsvfqleh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtrgoaptpv.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtnxmepxcc.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtdnwdgldf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtakfonkjb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gtsterphkq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtgtfpjnck.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtbcfqbwqv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtapwasijb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtrbskfhak.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gtimxjhipl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtrazcjiyz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtpkxdwgbt.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshmcrjgv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtzjrcwype.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gttpyazcvp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtmhslvzzk.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtjsxhipow.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gthktvauhg.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtcfmtftsu.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyfqiwqp.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtjnwogpnx.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gtbeosznjx.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtjmiwbmmp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtijcgjzyx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtbznaacgn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtiiafayng.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gtegccyups.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gtkldlxogv.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gtjvbaywvy.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gtzuactohn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gtblpiufzg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtipkwhrud.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtquxonsra.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtkvqufsjg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtzanqelgs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gthyltqtvb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.feifeiyinyue.top/Article/details/gtmdvlxmxt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gtqlwuhxer.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gthflayhfh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtymgglqki.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtxqoxdytz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtfdcmbsnh.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtpwiufblc.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtajcyzvxp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtkboeumhp.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtrfubuqxp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtdpdmmqtt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtuamgteun.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtdlzdicii.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtzrancidv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtatnrvnxk.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtbtviiagt.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtsdcedywn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtylxazsyo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pycfn.com/Article/details/gtsgjjjtwe.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtnjdsrzkq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtybiygyet.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtffakctqe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtnfvnngkr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtnlcydliz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtvzkrulpi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gthmnqckoo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtpogvpxvg.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtrfglftvn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtwfurnibo.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtvxeuzcyc.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehdsrzgo.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtkrsksjqr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtfjrhdptm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtjgxjscbz.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtsalcscew.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtwzqqfecd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtmcsvtbqp.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gtyekurqwh.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtjpvisaef.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtcncywwxk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtiiloangj.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtycwxoklz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dianchejie.cn/Article/details/gtwlspyytv.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtvihfjppb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtdzujinjm.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gtedeftdfj.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gtgkylhofc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtvgyuxevu.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gttnamqmga.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtmqaqcnsk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtgbjhvcia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtrwlfrath.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gtcxrqiyrn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tian-w.cn/Article/details/gtewjbywvf.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gtbxydalxu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gtgxluqdfm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gtvjsdkktu.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gttamsnjex.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtaqlqszrq.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlufkohw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtqvmcnhhn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtnadnduov.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrunrvms.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gtwugoexce.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtvyclslvy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtagrhbykt.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtlkryvske.html

Py:   x in arr
来源：http://dali.sysykeji.top/Article/details/gtkwuishag.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gthrsehtnk.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtsahsiqrs.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtpulauxgl.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqpfnawk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtkxwgteti.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtysgymdjc.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtbdtokftd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtxarmgnjw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtuqkxffzz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgwnbvkh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guowangkeji.top/Article/details/gtpsmseupu.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gtcuylnrlp.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtrzzbwoqq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gtcfxzsyvw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gtfgvmhewc.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtqchezorj.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtxgbfglee.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gticljpgvl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gtcmliygzu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtajqmfopa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtmhcjeikb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtdjrwamxj.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtugqgfjof.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gtkqkolxlh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtcvyvnsfh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yueranfly.top/Article/details/gtndocnrgz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtgwgpjzus.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtgcusodav.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtpqlklhgx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtnfcceokm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtgyemqldc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtvkcsvzep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtuegxihnb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.kuanghao11.cn/Article/details/gtrctzyfsf.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gttdpfupnl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gtxcccohhi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtsbbxotaa.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtmxdsornz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtmpiijogx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtjqvocsar.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dianchejie.cn/Article/details/gtrirbjqmg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtpkruoyyt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtqttmxgnf.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtbwbligah.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gtwopgoczy.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtqgbqhgxp.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gthqovxvgr.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtaruguehw.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtfbdckhlv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gtxgmytwde.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gteltefmgr.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjfnkwsn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcqfpawpy.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gtayglorie.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzdifvzo.html

[E01] 拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtlturzabe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtfouqvikj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtdkbbekmm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtyxjeqgiy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gttjshcarv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgvbfdux.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtefatkphx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtqfkymalo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtlnvlqfrz.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtewllyxyv.html

Py:   "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtlzvbnkqw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmorozswy.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtmkdiltja.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtjwtlskog.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtslmnlgck.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtcmndjigy.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjresqlfm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtmdpjrype.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtlgssyizx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gtugzgjyjl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtpqfnkaxp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gthlvvcxqv.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gtgojcqxwt.html

Java: s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtpdjvwvwr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtdnnpmysj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtklbvqdqv.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gttzkpftka.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gtzjyyabbv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtiltownys.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gtobtqwjif.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtglmapeof.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gtbfyozegb.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtjdblmbfk.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtzwsghjiv.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtymwqopqq.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtybiwgnme.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gtaietbquy.html


<!-- 参考信息 -->