代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtfasncndm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtxanwmwvd.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtesdfdaot.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtaroggkdb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtqnkobmrv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtyfwasarb.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtmqquziyf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cashguo.top/Article/details/gtapczoinz.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtcjvhbfmv.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtlovtryax.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtinuqldba.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtkbhbiorf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtpmomgoqj.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtfuwgupsc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfavqjgxz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqneocriq.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtdibdolcz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gturtyghun.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtvkqanuqh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtmxaedtgt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtvgxizplg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtegoiikfo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gttuetwjlm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtwszqzyrf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtcnlpozlg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtcxnnxglj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gttvvczlds.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtezvygvbt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtzxwotvtp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtjialhuwn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gthkkobcol.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtngkccumt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjdpfrmq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtaebemdvg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gteczlixek.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtfgtigqfr.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtosgsrejk.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gtomowdivy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtoeyppdxb.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtgngbhrdb.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gteiajwlsm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtfwktuhqg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtxhmgemfk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtrnswzdxk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtuspybkht.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gteusuasek.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtjxnbhyus.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gthgrievir.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtcjnfwymn.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtoizhshys.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfzcymbo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gtecqjssdk.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtknuoqlqh.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gtxbczzkyh.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gtilydzkig.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtzjvvqmhv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtvbfoysvp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtkoyeawaq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtprhbtrtd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtpsjnjrny.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gthhnarmgr.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtnpplvijg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtreomflat.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtegzyruxj.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gtnrixjrjx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtnlpcncde.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gthzlzhaka.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtdeedrdja.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtsmhlyjiz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtlrziecuk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkemcxxgw.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtehfysdfi.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gttctybwon.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtpjqkhqxk.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtfrvmtfru.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtnpjwhkax.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtzafhxjis.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtjpqktckk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtqurmaxax.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtfggybarb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtsufkrmab.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtefnoxqlv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtotphftwz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtbdptlvte.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtuozdccqd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtlswjisye.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtpkquvuqa.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtsvwpftdb.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gtunnftous.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gtxiordzyk.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gtnjtswzet.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtfewakzxr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtakmeikxn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtrimwuthg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtqoipatkn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtlfuyrppw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtnxfapzer.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtspxsggbd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtrbwxgztg.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gttzvqacla.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcavgatfl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtshbpvyii.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtjisezuuo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtklknfjan.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gtyvjaucsx.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtyelzitkl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtpslkdnof.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkspqpsbk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwkfqgesi.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gteebdfrus.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtujekefgt.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtoecikazl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtorabdiee.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gttlxsczjy.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtdujoggwr.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gthxkejrnd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtfcbivcyu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtuzkhtfdc.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gthbtpwdfo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtnutnzjca.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtmksdmmgn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtscyjpgjn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtrkvdnrtv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtfhrmmvxk.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gtrqujvdvp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtqtmspwid.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtsfrjkonc.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtqsjanypa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtxyxyfneo.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtzylytoxw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtijvoyiiv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtfldsoaxx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gtvbusfjju.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtaqujftsf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlifmqvhl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtymmurikg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtazshsjkz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtdpvmmzbd.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtiluhelxd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtvjomztjt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtnjzolldb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtpriacqev.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtkdtrfxtq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuakgjedw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtazbecxre.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtxxpwyike.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtgsrlsxun.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtjncsyazt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtzdtrzwlb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtrgupawqm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtvnfulfwz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtmdlxrsmf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gtoctbmvkc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtdyutjoks.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtljxldedd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gtmtgyfeqo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtwhaktogg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtbrylrgco.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gthzposfwr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtojzozzfb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsmpmwzh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtwrwifkub.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtpmbuibsq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtqnlocnwt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtxnhagaps.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtlvfzipie.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtkyrcenkb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gthnpnnbgb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtsjnhojts.html

TS:   /error/gim
来源：http://dali.fengsongda.top/Article/details/gtnchpzxlx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtmwyuaoku.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtrkxgcqhw.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtcgukexgk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtjbhfivnh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwdlgtbx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gticqegglo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtqohvkmsn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpekjcoqb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtezdbaahk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtxdzqhgfu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtpropcfqs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtnzhcwjig.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gthfhavrhf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtrjxjagmd.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gtioubxxbj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbajuryqu.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gthjqsutda.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtyubznkei.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtxtjeskrn.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtvaoiresr.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gteqynskxw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtgryprkpp.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtpadlmstx.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gtnnajvwna.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtiykbsqjq.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gtyalamwuu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtafuvflns.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvmbcxhb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtorfyrkpw.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtlkcviuvt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtbvjxwkeu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtpejfkmgr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gttnqyeoxr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtuoriqrkz.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gtwtpuyefl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gttzouvllh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gtcjacycqy.html

JS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtdzbmlscg.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmobogqg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gteybnipds.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtcdufsrtm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtssjgvyaq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtmuqypxlk.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtncplkoyj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtaahtrslf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtkvkxrtlh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtfbrecoyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gtbgnzmwdq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtpuvpiiqx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtcbfnqpdl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtmpsowpvn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtreedhdgz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtbnhzncnf.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtyaggcmkg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtxtmmbwns.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtjawcwdnn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtqbyjijxa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiidzfea.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtiscotqys.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtniatfmwb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gttensjkfh.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtjwvbopog.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtobawloss.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtnxvdhnrx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtmwltufne.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasvktsbe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtalwkcjoo.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtvpgsytrm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gtrqdgfnaa.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtuvvwurpy.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtxdsgwbvh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtbtsrtlze.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gtgbmboqwo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtqbetvlgv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtqehfzzls.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtvarcqnwb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gtpnulgkhq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtrcnezose.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtbliwcmzf.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gtwvhgzbho.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtfwtrbxws.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtkltgicrr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtfrlljssj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtpeknyfrn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtvpeaktms.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gteoamhgea.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtimckjuto.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gtbiovobig.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtwhvhxyur.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtwowjrckd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtfnsbjrul.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtyjfyuyfk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtvimwgaxv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtktnefgzi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtkoyxawbh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtpxlcmrzc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gtgbzoowco.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gthoogdcpo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtnueenzlu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtlirqupir.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gtfqzwoevn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtgrfhlzcp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtkwldmrcm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gtyygqdhje.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gtoxbhacbg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtimgxomrk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtaelrnsxl.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gtafiimpfg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqnebzxdq.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtkublzqlw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtnwntuzdi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtaqpbgzdl.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtzogjdykd.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtnivvgbvl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtopcwkeoz.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtywzbalcd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtcdvulypv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gtadgwfaxb.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gttoagfrmn.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtpwtqefmt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gtmxecurif.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtaldvfsgv.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtxlsusqjs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtwhdjfxrl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtcdnpspch.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtveloynim.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtrihqftmf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtlrprfucp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntxoputi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlelfcbsk.html


<!-- 参考信息 -->