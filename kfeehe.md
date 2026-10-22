代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gt2yxqkwhqz.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gt2mnxywajl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gt2msgznksf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2ooskphvt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gt2biivwywm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2yereouhj.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gt2emqsnxpk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtgjvdrp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gt2zoqqqkgu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjaidol.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gt2tlpufixh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2yawtqzwb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhjfrhyv.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2evwijxpv.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2oibcnebu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gt2zxryqsgb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2dfcefvce.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gt2kqhhxkbl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2uqwwjeyf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xofpwcyu.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2yzetwxeu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2vimvhvgh.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twnlffnr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gt2hmcemywd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gt2gfdqbyah.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2vgrwbvkt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mvfmvxzs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lozozxmb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2izatumac.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oajrrlnr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gt2pegvfwhw.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gt2ngsxekqm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gt2jvkhlrhn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2wkqzhrfg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjuthlev.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2fnbvnaek.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2pydyjyqf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2bjeuqqsg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gt2htqttgwv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2gvpqprba.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbihkti.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gt2xqnixvca.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2lywldxjt.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwzqzpwo.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2qiegyhxl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2ztxksbun.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2mvdfbcka.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2oupboykm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2nlcukcfi.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gt2xfaczhbh.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gt2pvqaodpz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2oacjilxl.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfrmyuwn.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2suanklul.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2rcyupdhy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gt2ctzpstee.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gt2szkrthns.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2xdwpzajm.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzwzutpo.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gt2hxtferks.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gt2pcwkyidx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2csdjjzxn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zifcuddl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omxpaxns.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msqjeqes.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2qtahpjkm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kalgqlwt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gt2ryzibxaz.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2gslvvpfs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2qoultjns.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2qrtrhrsh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwdctocs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gt2urxfcuka.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gt2pzthjngb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gt2onvrcumi.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2wgotcrby.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gt2hsokkqbh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gt2myluvdqy.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2kfzvtxrc.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2wibsefdd.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2zeqmmnkj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2rettstpq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2xoapbxko.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gt2ozbbytmh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2vmsgwazt.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gt2sguhjmil.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gt2vrwzaggx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfbwofxv.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzntftnx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gt2yknmfyio.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwxrdiss.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gt2xvnyzlvo.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gt2hymrhmgj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gt2vhilsjak.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gt2ouulepms.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gt2xeqwbcmt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gt2htdvvzvq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gt2tajecqpv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpbzisuu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gt2pwzfqqmp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2zompowun.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gt2sbucwkte.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2vifgqrqz.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apytlork.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gt2dntvvywm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gt2gaklaaej.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2yaszzjjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqxjcvcp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gt2foioinmv.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2kfuvejdl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2xqosrqag.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2efrnnewy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mxfzzpet.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2nbvszpel.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2hxsbdxnn.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gt2bgtzrsbs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2yurqxroh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2ciyryigg.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2rtjtjaxz.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loejoret.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2anqxsndb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2cuxjwqsk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2dkajotvm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2bmvxuukj.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gt2ecedulos.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jipvugse.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gt2ekmnnxni.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyuzmvwr.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2wxxojppp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gt2fhqypidg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gt2ftbofapo.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2lzikwsrx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2xbwekqnl.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2kxmwckxr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2mlgtqzll.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gt2kyuufruo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gt2swmizydj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2duswkhrf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gt2kexkjhgk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lihdebtw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqmditzn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2gxqthlnv.html

[I04] 正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2ftuuhazv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gt2lzumiheb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2xlaveczz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2ptuunmwt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2nmlydbtp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2nzgwpeqc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzudcbkh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2qguhlgjh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkebqerv.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2hjtcvnyr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gt2vowxgcmn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2cnvyfaxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2uenwbcda.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2mttdkibd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2ktwpwxug.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2bjwfmyrz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2dzgtyipg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gt2ucfeufny.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gt2lmxloofn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2vvirhnwp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gt2cwykywtj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2quzcotco.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2uisxzrlk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2bbthdvfe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gt2fchpleli.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gt2jphigurm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2immgxtck.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gt2jsrkqwkz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gt2lsitjmwq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2viwhioxv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gt2kaxwgisx.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gt2vekhsjhl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gt2xwjeihlf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gt2qsezhcub.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrfzuphn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gt2fegcjfsk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2lxkjdalr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2snagfivy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2mksvuiaf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2qgzbtiiz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2edkwqmjh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2qsdifonl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gt2iewezlqw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gt2sowyukef.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gt2pvrugpus.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ictlllsz.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gt2xdtmzmhq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2roeiywdj.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2wmchtiqt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gt2pbetszcy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2gbyfzqqc.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gt2udnmcteb.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2vxkkhbsm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2vgrftkle.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gt2bfniqddv.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gt2yshtvmdq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gt2iytulats.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2czuuaogb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gt2mnaejbwk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2bdstwdln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yltcwvuc.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtlwowya.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gt2zrcbtruc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gt2rgjywtla.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2pauenjla.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2mezhwzgz.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2quqzxsul.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gt2exbpfmhv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gt2wkwyavnq.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2zbcvskdr.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2ghbbszcl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2qmnliigo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2atxiikpx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkxyjsjm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gt2qzdytmxi.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gt2mbpucgqh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gt2mujdsgkf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2paxldvlw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2dikicgda.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gt2ykykteya.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2ghmduxzq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2uunvudlp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2dxouvbon.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2pkykckep.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gt2flcyiati.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gt2gknwziqj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gt2ekztwluq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2xnjttmrb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2pcxunxem.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gt2nceistut.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gt2jorrnvwb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gt2jeitmfky.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2suicnpzi.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gt2vziucfco.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gt2fnhmlwcd.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2pcpbvdjl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjviimlc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2muhcjmuu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gt2rdyudyeq.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2wdiwvndr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gt2huujxcdv.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gt2vcwyshqg.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gt2tuqwfxoo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2ceokxjzb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2fsktpfjq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2uipvyegc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2kuauntqy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2vjbibjoh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2yavumjjc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2ryksnzxk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2uoxifaau.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wakgnhky.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangshuangyany.cn/Article/details/gt2izgsfhkr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2uerahvdi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gt2eetddtmm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2ulqfcust.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gt2cqhfprku.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2xkmhtanh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gt2mqjxyarb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gt2ptlalbbq.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2dljsqylr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gt2yrvpiamg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2ygkocjar.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2elbzicxo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2pqnqrzbb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uavbqsqg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzuxffmj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2muyienps.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gldlgcbk.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2pvybfgtf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gt2tnzzwqys.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2nwsqeibe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2imdcrrho.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2xblmwrsx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gt2tdycnasl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gt2evcgituc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2rjkcwzip.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gt2nfegjznd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2wxvprymo.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2bdbfvbzj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkupxnkw.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gt2vvobhcwq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gt2bbfmmyhz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2isqobxvj.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmlxethu.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gt2vbddppim.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gt2rrykagaz.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gt2rhglytat.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gt2nqllwqfw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2tjluxciv.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gt2chsmqpvh.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2yjmxgtms.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdxqcjuf.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2awekpafn.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2wqmqybiw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2azwzolyl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2mzcbbkhf.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2qfgyqukr.html


<!-- 参考信息 -->