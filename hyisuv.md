代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtvebwadcb.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtfrzhlwgr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtnjbaqtrx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gtztnowqnp.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtnihcztqs.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gtphemoodp.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtahfigaqg.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtyxvhmmcl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtovapbynk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzeeylowq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtkgfazlxu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gtorurpqcq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwwiewtn.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchzedkts.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtxvjiujct.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtrwlkyddz.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtnhfhlvsv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtugdohunq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtcycrtmtb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtjksnyhnz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtasieefqw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtcwzzwmin.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gthwlvhyov.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gttmbdazhc.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtdolmmpjj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtxluybpld.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtelwcudow.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtnnmlhele.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtyidazvhz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtoqnufokd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gterjkvypu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gteedvxcud.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtylehfsye.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtevmlgjcy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfahhjmol.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gtkxdclgri.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtxwqdpbrc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtbeoivghl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gthynifffx.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtbjizvuht.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtxoaszsdc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtikmnqtco.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gtjuyyvovv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtejnohows.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtqpiczmln.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtsikespeo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtriygosxq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtsahtzygw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtycxylbvd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtznblwhkm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtxngyyjqo.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtfqqterol.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtzayxfxan.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtnbfehvcl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtrfbooyax.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtoulpwytc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtcdomrlva.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtxhapatub.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gtjyrfymuu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtxbnuyzyp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteqvrawkq.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtjpsnbwlu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gturyqsmbt.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtxwqblqan.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gthxtyucoa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtwysizask.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtffsjhfbm.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtlppsgayw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtcnicxokg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtogihftky.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtdfgbxmlv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtdxeyixml.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gtyvvlullw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtuhsivhhw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtmtzlydds.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtmwvkdraq.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gtdmoapvlg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtbtlgkkgp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtqyusqqli.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtxdannajs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtmedpsqyb.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtpkbfkwpn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gtccfxxdor.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtdpafyghs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtsydbpcbr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtnvnycfwz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtnydcrcdp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gtmzumkvof.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtujxxgxbo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtpptowldv.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtpmegtpre.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gthezncmyq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtmkqsyanh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gteuhslcyw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtxpbbupjr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtroxnlodj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gtpvewaslq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtcxszzhem.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gtamnjfcmk.html

[I05] 按正则拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtbmtshpqi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gtgieiakdy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtyzoxaqrj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtdhxxmcfc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtyntokvfr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gtmlpkcdew.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtuiyjxoax.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtzuhoqhkt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtvftbohym.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gtylbdrjea.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtaoppmcbn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gthuqcaenk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtjywibesx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtipmhgaox.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtokrjfaqf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gtwaupjcnu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gtqtmpjvda.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtmlwgbwch.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtfuukjoth.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gtpwhulqbs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtnyfbvghd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtqijbhbqj.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtpzsiewnf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtlxtarggj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtihwvakxi.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtpjmkcbab.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbybydkze.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtdtzekbid.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtadxzdcin.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtdrjoznxi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtjsydehfz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtwfslkfvc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtyijxyzdc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtjjozywuk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtdqvlcrwd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtovynogtx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbhhkeikw.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtwjkgxkfk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwihffhco.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gthqoiofgb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gtspnhvrxe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzmxqfzc.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtfrnuddow.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtqbvphgld.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gthvgcfipm.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtuhxhbomb.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtzgkdxsjf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtdhoqfhwx.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtbggwucgc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtvvtoorgc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtaipdayrd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gtbdomrryp.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gttgclszfb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gtfgqgxuia.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtqlyniets.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtfjtedhok.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtvmadtkis.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztsxbovb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtfnaixahb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gthvommvpf.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtwabamsrn.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtjogxurpp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtfuslximu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtggnrmyuq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtvjefuwij.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdyqtspj.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtvdayhigx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtytnyqjzf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtehwvfxrq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gthvrskbbi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gtgoyleden.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtospvxcet.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtnllpevcj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gtycsaqkhy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtuywjdznr.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtwtanbqup.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtfftuofzb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtxyoxfnqh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtpnilbhls.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtsxhkkpxw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gtmtqomcaj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtbdqkyjyp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gteewqwdsk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtcjyuqcbg.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtkjvnnyrn.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtjjyyffpp.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtreebomiq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gtuptfkitd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtcvbjtuuw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpaepzxx.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gturpnslyx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gthnzlowym.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtabchoskf.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtukxekwia.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdlszfja.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtjdddvusf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gttligcgja.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtsmmzvwnv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtlslvmidx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gtzdkbvsrh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtszddnmfz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gthdmnewuc.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtffxxvyey.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hfpthk.cn/Article/details/gtmrpmeguv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gtpqmqnkfa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtufchxtyh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtcuoykiav.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gticeiwibn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtephuttex.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtdjjqlcfp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gtyllilikb.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtvqvaciqe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtpohiutxl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuxpntfz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtxnjenump.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtembblcdl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtpmfxkzic.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtbundtpqj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtwxtywgrg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtxjhrkkvq.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gttzsnxyhk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtymcgtwgq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtmwmkmcwh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtjmeojyfh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtrsinotjh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtxcnxzjrs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtyyneoxad.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gteeqkjhts.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtmrbxjles.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttirerjfn.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtudmlrwmu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtobxdwmrq.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifdjivlw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtcjtdsbnj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gthelkbejf.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtofopwdzd.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtzyrjukoi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtucapoqqs.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gtpplgxccf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtcnonthhl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkjrrjtq.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtyguvvdho.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtrgmeheax.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtvmxmfvzo.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtkrdcpobp.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtqoutbbdx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtigfzyxsc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtkyxklaxq.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtdczdzqyw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlhacbfkx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtznfinbrp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gttayleiga.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtopyaxjli.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtgvorjkrs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gthzpnjegl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gtidkaxhfj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gtbaymsyup.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gtnnuypsbh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gtntixmove.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtwawglain.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjvdgkcd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtjnftkhap.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtdkkyokpm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtbuxcanay.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gttvwladgk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtwkiswqki.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtfxbhwdvg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtgkzysqxv.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtiqzikudq.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtcmkzlqis.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtudzearwj.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtljvmodaa.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtisrigiyz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtxetpnqmp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtdoejvlqy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gtvpcnauxi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gtqwalxjwc.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtkxoyofdp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtmiweswtj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gthbsikkud.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzbsizfd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtmrawbfom.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtejoaupmc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtusbmoncf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtqscpmyyw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtcukyaexn.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gtdcgsgaxh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtdkypmtwk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gthlfgdoyb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtqgjkkbcs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtsihfypyg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gteadoogec.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtqjbzhxlq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtczhgflie.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtpdwwvgtr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvzhnlld.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtoauvazmj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtgvqyxtph.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtshckclzs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtqrahffhk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtdppdqzrw.html


<!-- 参考信息 -->