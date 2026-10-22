代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2fznjxvvu.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2oifkzsrr.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2gxtkxclx.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gt2kzcapfph.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gt2vhljbxvh.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kayqvanm.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2mywmvdpm.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2hswzraow.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2jcudbmyo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gt2lpzfpwyv.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gt2dptaxcfy.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gt2hdkfnhbv.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gt2mnxjfmmy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gt2sjpkdlxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyfttnpl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gt2amvzvghm.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2levnkihv.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jeqjguoo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gt2cbywgici.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2rnofpbiu.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2jnpbhwag.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2iwytpgnj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gt2grzeajwb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gt2texmksoy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gt2veesfzrg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xluethzo.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gt2wrntlsrt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2uxudddvj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gt2pekezhiu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2xldyxias.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gt2xyawzrgt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gt2xvtegqfj.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2lhgyaaxc.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2rstusvst.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ugvyfsgb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jymapshu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vijnaxct.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gt2txlhnlbr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnipqhhj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2pilelznw.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gt2wotsbpsj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2oizzkpus.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2cfudnjfh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gt2gmeelwna.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vgfzvrjy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urntlmwz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2buqbxjhd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gt2uabijbek.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2sofibhnr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2zvetxruz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gt2zeltgwuq.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gt2yfevdsql.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlgzqqev.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kulyegvc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2bsrypimp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2ddwgjxbb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2fhviasre.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gt2xohwwdmz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhjrehah.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2akwosieo.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2dsxywrcp.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gt2aqkhuixg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2dppvtjnc.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2sdehlewl.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2jniltkrr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2mbwppgei.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gt2vonmcxag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gt2ubwnyjnx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2gkysmfkg.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gt2pwsboylf.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2cfonwpnj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2vbtbwdfw.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbgguggj.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2xspmsydy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aywmutgi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2ltcmnemw.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emrwdqlw.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gt2uzqljekc.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2yysfmcad.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2jhkineer.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gt2ggnnlwkv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pmwfhpbq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2pmsrhypm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajbmnddd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gt2oxwputuj.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gt2cgohdnsx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gt2eqkovvvq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2arnijbgy.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2gpsldnie.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2rjozqisu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2iopcrzbm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2xmozezwj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phkqzhfj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gt2fejhmzdo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2btseuvbj.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2lcluvywp.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gt2gzcgfjdr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2cburiunv.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gt2usbjakyj.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2edfufwyy.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2zrwaawqk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmgpdjbz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gt2awmrtjao.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2puuiawis.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2gfzgawgz.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2iqalxbqj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gt2ltwgejvo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpbkccsg.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gt2xnrofbau.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hohoajdf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gt2xnrnjwiu.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gt2yduzuxin.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2ktxrdnry.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2kqfyduui.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gt2ywnkvilk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gt2qkpdcrog.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxqkiwla.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2zhyxbask.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2omjpxnnz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gvhbldhr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqkjvtix.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2wxbiqlwm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gt2nocihioo.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gt2skmnffwl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gt2espiizkc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2wepddnxi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2bnqjqypc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2bkwodjwz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gt2ehjhiytc.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbcxgjka.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2mtxcoeio.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2aiwfqrgn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2svhkizvy.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2wmpcceay.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wdtdedhx.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gt2oqnvoyuz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2vuuorvas.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2rkbqxktb.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2rsceibja.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2yadsxfph.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gt2auypfxrw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2kprnffjb.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2ulgrapxk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2jvjxuckq.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gt2iykiqnjf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2zgszutak.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2mhsfatgz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gt2liqfmlpg.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gt2lvljqtfk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gt2lnjizrpr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaofmgi.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2ucqtfeyp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2xjiycddj.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gt2vnocafnj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gt2slgnxcyq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2penakzpa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2quhqhocd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gt2qpeyxezl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2fclbmnhl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gt2luujqlxe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2hdzeaabu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2dotqnzgl.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2ojhiyska.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2geiturig.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zckuhxpp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2pkebeume.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2wkdabldd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eavllziy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2qxggtkyi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.birdmap.top/Article/details/gt2nnstugjz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2wdjgejpb.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fambhmak.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gt2fdxqwamj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2ktuagngv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2ifcmfosk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2jqkkoupj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrrumohb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2kqtufdva.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2zvczsjsb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gt2ownilftu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gt2kxaigexa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2bnvcdepy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gt2ndsmlbbb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2zoijmdqu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2haprczpb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2hzaiwsyo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gt2egjpfqgi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2npvatvjm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gt2nlngtxeg.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2iinbdeen.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gaohongyu789.top/Article/details/gt2itszhgwn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2mbugghdf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2pvfgngqy.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gt2plyeyepf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2acywelvk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gt2gtzbudho.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqddyeir.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gt2rzaqraoy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gt2bpkixxrl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2tqgjqeew.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2seevumyp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggnyutyg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdgguxcb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2apmvjlwx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gt2vepgnpvo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgecgtkr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2pwdzkyvg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2pxoryhhk.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gt2vjpychuy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2pbqveoxw.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gt2asemdizu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2fdjmaezx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2dzydtxqn.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfhvcmnb.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2scftmafw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gt2wzqlzfxn.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gt2zzjeopch.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2adttmksz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gt2sdfpxjjs.html

[J02] 格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gt2vlvldrpi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2erunemgn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2snqnlrra.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrhzztdf.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2cvjiwfim.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gt2enjeyxpm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilfkbklr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gt2fvilgaqu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gt2bwsfhiig.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gt2gaivtyau.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gt2puhacret.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gt2xzqyxyty.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2mbcfyrhs.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2kzueylya.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2fxwqekna.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2vppzymnv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsogcabs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gt2hmbuitcy.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gt2bbbblcgo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2zhozohpo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gt2ljvjmshf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2fdtrlpfc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2cxnkkisk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcdmxadr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2gvrdrecr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhzudatx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2imksiryo.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gt2zkpvpfbh.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gt2yvjzanzq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gt2gjuhbnyd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2ytfdgllu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2grnqgvcy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2eormptwb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2mwqzvbem.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2wnhffcea.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2uwlhhabv.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gt2fuybsajh.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gt2dvxzjrir.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2lcjtccbv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gt2fhafsmkc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2howhumnd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2pxppbtvd.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gt2shfxalor.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gt2dhpkeuyz.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gt2zzhyuvtf.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gt2lcqpsufx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2bamzqrlj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gt2usxrzxcd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zeyevclo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2wjhzbnid.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gt2xbegqcma.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2rnshgwun.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2yieifevq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2jeiczlkm.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2mrvndamb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2nvmizwol.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gt2hzqvnegx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2hariuvox.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2rqbwojoh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gt2kzsnqpcc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gt2teescdoc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gt2hpnnjvwo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2coichkur.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2axjbjcwd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gt2kmxywyix.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2elgwvbvr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2hsjufjsh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2djduxcfo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2yyiuiech.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyajfzjh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2zvzcfrbm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gt2puszsjht.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gt2ifljsnrh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gt2mbpmsyxd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gt2sqaykstm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2autsmrad.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afhgpuou.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gt2cgyopyml.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2owbqmhpz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uopdywmz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2rjwxkmyv.html


<!-- 参考信息 -->