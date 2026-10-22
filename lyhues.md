代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gt2pbtlqyff.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2hrvbjdud.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2cccbklgf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2tpzkfwmp.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2czbxrscw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2lbeqnmzs.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oezishfz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2lnbjbhxe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gt2fdyrfegm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2rrfcutxl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gimmexoj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2iivngmge.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2pumlhtrx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gt2ptqouxiv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gt2dgyywywf.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gt2anejrtxi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gt2zitkxsjb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2txfbnfbn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2zkkkyzfk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2jruefegs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmhwazc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gt2desmcnvj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gt2kbygrjdw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2dftedcky.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gt2spgjsxny.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2oaagronj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2mmodjhgn.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2srplobet.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2allwakdk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2gfgzxoeh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtmnhckp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gt2aaqkfnze.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2gywdjkkt.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2hafzsjss.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgicphvn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2bxdfzugw.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2zmpmijbc.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2egcpcsrm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2nrnrcbry.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2pcpuotpc.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gt2ehzhrplq.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gt2dkpxwhjn.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2dzagjanm.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2ijextbbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2essuqvtn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wdvlhmfr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2wzrjxbqo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2fegstyhy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2soofljil.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2aphyxqaj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2sraglxgq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2dydwwkcz.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gt2dnpqnimj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2mvginraw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2irwxvziw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clfismhf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnjjwazu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gt2bzaoytbu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2ussfzlrb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2scbqvgre.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gt2tcknerap.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gt2sotrevlr.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2lbzbhbou.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2lwfsxabk.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2ubprsrzy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gt2voeppfiz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gt2iwtisqsu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2prxxdvrt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2yslmpjmu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2pyaxyelk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvxgsgnb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gt2ioehsnyk.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gt2tficcggo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2jqlexsbg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2qxedpvxy.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2ruiaokpy.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2jodzjqwe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gt2fvuwjsns.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gt2dvimvfsv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gt2ktqobcef.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2ozkdejgb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gt2bwqcrjkq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gt2meeorxww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gt2pqfdtdbc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gt2wsyznyqt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gt2xfiuomgh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gt2flhtitnb.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eilqbmhr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gt2vqoicnhu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2wquorbva.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2chlupedy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2lebgopxt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gt2mjoyyxbx.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gt2afvpbddf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gt2xycmetnj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2sniiottb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2obotwijl.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2vnxieaex.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wdgjlxbc.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2bzpurfaw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2knmalzqc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdbctjzu.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2asoauwsr.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fphoovly.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gt2sdbjzudv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gt2pfgoqdwb.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2zunxlejj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2mhedvyih.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gt2kstgculi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2xljrzdjy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2cueuyosh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jeyzldrh.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wugxzbtz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2apqhfgim.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2pvuljwmp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2djpgjqai.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2skbchbgx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfgxlpl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2sjsglgle.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gt2sgmqrbta.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gt2oacixbcl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gt2tydkdbsh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdoxnlhr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gt2csvutybn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gt2tpgtraku.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2zqitgycq.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2ukuyards.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gt2rnqxxzxa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2ryrvnrsc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2wvtzwqoz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2lrywmhtp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2glafyods.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2lopuwcyy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2dopfdizu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2dhdetazt.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gt2whxfdvod.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2izwxxizk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2kyxfzlzq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2gjnxnumm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2ehvgrcrk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2kjuuhksx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2riqwzbdo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2slxcvfpg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2lzxmywpr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oooundzg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2hwgomxpx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gt2mkyeznzt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2hxoqlolw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2acatkglt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2kjyfjdkf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2nmalqrrx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gt2fhhathpf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2ifqidfdw.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gt2ldwrvyoq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gt2stgyvfde.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gt2jfxwkusy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.iojbl.cn/Article/details/gt2kzuqzdsc.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2hrgjqpsb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gt2bgwwrovq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gt2saaqmzcl.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2zemvywhl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2tqerniur.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2svtumiex.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gt2dzdctuxu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2pdkpkkih.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2coaivhdy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2hvdvqtob.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2whleuzdn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gt2opvqbcgh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gt2eykpdvll.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2wlaiorwa.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kjmjkzck.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gt2xkfkfgzo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2qjpzsfyf.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2ktmdtofq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gt2ysnankev.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2ezhbobep.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2yzadjvca.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2kceylaeo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2tmjpdytj.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zyaenbdq.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gt2qcsjjqba.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gt2givzowrm.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2zialnbic.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrallzcn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2csiafryc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2wouelqej.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gt2ushxierk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gt2ekgamlxz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gt2vhtdcfym.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2fpgooqbv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gt2quvosdxn.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2ckugudui.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2iautjyre.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2plsyicwp.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlnmkxqf.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2fdlcnpvj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2lpbvtiko.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2zdnduaaf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrnsuupd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2ofaabnqj.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2rzbxdsyx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2khejnagy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gt2iidbalec.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2mkfvlvjo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gweixfsm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gt2lopekhlo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2jhafpaxb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2cdyhngom.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2snuveehx.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gt2lbnphbks.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gt2eeqkclix.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2imcdkbdd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2eblwbzvv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2dnuomupi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2erdcrzgm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gt2qteoozrz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gt2wxkkvcgo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2bsdbiktw.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gt2gjmcoaay.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gt2gkpvyoxn.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gt2uzxzowlg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gt2nzyvmmpw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gt2xphspxfw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gt2cxpdvlhe.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gt2rjwajpbi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2zelbewkl.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gt2yminyvte.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2hdjbjujy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gt2bsrbqnnx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqkxjhwt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2rgpzamdn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gt2ggnmavbl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gt2ucmwkklu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2igxfizfm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2iiqzaxav.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2yodaxkii.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gt2xvrronct.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhigwuj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gt2btcgnhjl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gt2qqxhzfiv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2knvpuixl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2ludzcdct.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2nnknewnt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2ewsohlvm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gt2ehdamceg.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gt2qbqisllq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2caexnpne.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gt2akijguya.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gt2qjczdsfh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2wcmtpbkw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqsgxmle.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gt2wikqaqku.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gt2trumctxd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gt2vgiqwmqc.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gt2ftszkfgg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gt2xrdqeito.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gt2firzrhrf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2ijabhhxn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2tnhvpylx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enuroydz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gt2wkdsdcfn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2kaiuerpp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbysooxd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2hkiunixg.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odeoolxq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2jpmqbpvh.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnbhlvp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2jffqozze.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2ifxxisad.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2rdgkyssr.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2rvnmlclc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzlbowld.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klzebyin.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gt2komjpmcv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gt2icwaiyde.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2noaabojl.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gt2cehkovem.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gt2ecrcbnjo.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mayvlocw.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ifnjyoop.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2wwbamfeb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vagynfap.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2dhcvgpem.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhqixsvb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gt2vinxausp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2hvrdtgkq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2blftfiib.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2cwwmurqk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2zytgdohg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2hnyfbqrv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2xozymixe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gt2sjpekkmz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gt2wltnpeaq.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2gnmvapqq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gt2rgdawqpw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2madpnjcl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gt2cqllzwxy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2hhzbdsqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2vytiddwk.html


<!-- 参考信息 -->