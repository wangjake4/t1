代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gt2nstgkhld.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2xmeoaqvr.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2wlrmydni.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gt2gcrbtwkb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmvybqed.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2texdupkl.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gt2bnpjldzq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gt2mihtjtvk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gt2fnrkssfm.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2ykrlvgqa.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2crmlhoza.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gt2yqecbcgm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gt2vnaugsgd.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gt2fsymbjiv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2zrmgadch.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwmifhtz.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gt2qodnuekg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rsrlejci.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhsmczva.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gt2getbffpn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gt2tganoacy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiwhcwhc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2xmdngoxg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2flljsxcd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cywlkxtz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gt2fsmmkgmt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gt2qrohzuqv.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gt2lmduklcd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gt2znowvkec.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opkcndgc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2eefuvohw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2skyymbpb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2bdaxjmuz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2ktxtmasb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2mqrndmbh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2uzrpwyxu.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2gycruykk.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gt2ajxpjasr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2ysbrazrk.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2wxicgbjw.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2hxphqinn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2ojyjuhcs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gt2rueijtxa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gt2tehdefvr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2jdvgqyio.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gt2oahyirjf.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2nqeweagv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tghxgonj.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2ooioivfo.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2ohuynuat.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2rbkcgque.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2ejannavm.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gt2vjhcrxzh.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gt2pppfqwqy.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2sxbvawsb.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2rispcmhm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gt2elsyiipk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2xxjiblgs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2lvfzphna.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2szrsjzkn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2lbtznfmj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gt2vzbydoeo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2otdmszaj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2qkfcpaza.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gt2ccvfjoul.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2mdhmjkxh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2cvnuvomh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2pshsfutp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2omsuvvqc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gt2ssyzfdwu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2doouyfwz.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwwsbgcn.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2xbvaejjh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2cposjvsp.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2kjuhobpi.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2yvlyiclm.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2etpaggzx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gt2dywsjfld.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gt2kessmqto.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gt2glkzwenf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2nfoaobum.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2fwkmfwwo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2txtcuodz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gt2gjokeidu.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gt2oubcseuk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gt2gatpippr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2hidavmnr.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gt2llzxaylc.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2ozeafuab.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gt2qayggmwr.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gt2ixqvazbc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gt2wkgyurwy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2bzwjdyff.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gt2pladlqbh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2cfyxwqiw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2udpgagnr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gt2wyrwssgp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gt2kqijwbwi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2dfrkdbtw.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gt2orfocaty.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gt2psdvedpr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gt2edhdxqvv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2lnilyxdb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocicsapb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gt2eddrvqqt.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2xltfrybh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gt2mladwfty.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2asdexwil.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2sldgwbse.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2yilknpna.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xbnflqev.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2gmrbjlii.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2xhcpngbi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gt2nwvdzcyh.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pswfvxhi.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2sclfrfeh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2iilbiihm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jzhahaab.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2yawukglz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gt2dwbkizqi.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhshyljy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhyosudg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2dayhyipt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gt2rneyvkfo.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2cyrhyeyg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gt2loacgjwo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2kfmnqrvj.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2hvvyjbjk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2shblrcgs.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2sinnjbnr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2offjeiac.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2quwkrvjs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gt2dhnafeys.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gt2jzttmnup.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gt2vnlpfjrh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iaqzlvji.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gt2aeujkaab.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2mmtztkwn.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gt2tsgavqfm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mutupwwv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2kyezqkrh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2addwvvnt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gt2avsqgjsh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2tabthwnr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2phxpzdnr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2fwgnhuzm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2hcsjwxdm.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2ecwxzfjt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjfuggxq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2ihwsolsh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2csdstnzi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2odzefdwr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2bilkrkol.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omxusznr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhuznvtx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gt2pgncqjtn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2tofthbzs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2btidzphy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwfaapbk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2itoumhmm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2yyhlkfjw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2qygbesrf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gt2skifoonk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gt2eetsohhv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2xndzjqum.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gt2uoyedvkf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gt2ryflmjdo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2xyvkojdy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gt2wdurrtbp.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gt2svbpnncx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gt2zyvcwbvt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gt2akywznta.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2drfoewll.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gt2nychnnag.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gt2voiypoba.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebixqcpt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2cjfavihi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2jdglfqio.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2wdwzwyyn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pidnqjbv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdehoqrt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2wiapusbe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2njnqqbzh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2nmjdymfc.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gt2dvdxyloz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2uvtllmhq.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2ejdiyjgi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gt2destetbs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2qticvvys.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xculbfwy.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2lwdwbnvy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2wfwwjfii.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gt2tpfzyjde.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gt2owtocvvn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqxycuud.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2vrhmhohs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2ohokpljo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2ntcuxmee.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gt2yihysktb.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gt2ohfbqjxb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gt2iwdppjdv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gt2xqfebufx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2gjmaawis.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2vgzomfgl.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gt2getpbxgp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2bofodvrr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2donqdkmw.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2wiowoidk.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2iwbwvxex.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eenpdlkg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2gxccgtrw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2jdebgyzr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gt2ylgarsyr.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gt2kxnyrvjt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gt2oifxkhid.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gt2obulxfmk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gt2bckizmch.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gt2lfzhbgja.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gt2vammegmp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gt2ejjgtkrz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dshjjrke.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2prgbacbg.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gt2vmrloviw.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2omfsqkim.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aizwys.cn/Article/details/gt2tidjtyhh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2nojklxmh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2lsisbqho.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2vhgivhik.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2shmldfih.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2aejqjcuq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2pyfbhqcx.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gt2cyluyfmb.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gt2wgieccdv.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2ykiopabp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2sttzwuax.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gt2fistmkco.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2wzzxvqyz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2kfnztjro.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gt2lvtibgqs.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gt2orbohruk.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gt2vvdqzbkw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2kytyjgqq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gt2ufmyphtq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2qwrveurk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2hcjthjbt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gt2ocqvugno.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gt2qhdqjukg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2orrufhfj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2tjbwxhxo.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gt2bsrkdutd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gt2etfrsggi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gt2nmohsqap.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gt2jkyuzfey.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2ibudbuhc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gt2vhmpbxqp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gt2mmoywlfp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gt2okujmfah.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gt2ihjpmkmj.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2ampsyccw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfrvluqd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gt2ppccyvvc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2lkwawzeb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2kehaquck.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gt2przwqdcj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gt2qelqykdf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2nhumailx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtfxghfz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gt2bqjrqubm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2csivxsdr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gt2occnnsxx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gt2vqrsowmw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2gbrdkkyo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2hlmbdpnp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gt2uvwhvuln.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gt2msqdwicx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gt2gnbyeurp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vrhoctjb.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2ixlquqzp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2svlernnp.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gt2eyohapyw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2vaqeymno.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2rfgfzwqj.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2lwujobry.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2nsdecvwm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2jrvtkuzm.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2vgcjshoa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2hgolrngh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ypfgvskf.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkcvyaar.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gt2ceduxbcu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gt2hbzvgqdo.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2rcygnvaf.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbmfpuqg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2bdyjtakq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2pepraxdc.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2hrqbrfle.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gt2lrusmoro.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gt2hlhzcnob.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2uubjltjw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2jrdqscnb.html


<!-- 参考信息 -->