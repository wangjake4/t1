代发 wailian999

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gtzwcahmof.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtqaentdtc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtjngbtson.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtfwnxihgo.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtcnbrhwzq.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtycdaftzh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gtwycedhuu.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtrfwmexbm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gtttemfdgg.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtttbdiizd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gttelqwdzm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtlrtqiaqc.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtrclxjzeh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtedmhxnhj.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtrnuobmdj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gtaydhogwl.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtpoeqiirh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuolydqwf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtwovhgolr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtoykucpay.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtzwuwjafo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtwalnrfjc.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtmlijrndl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gttourklpa.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gtlcowzhpo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtnnmaflpz.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtubhqkeiu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtjwyqbdef.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtggwqlegp.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtzcaqgtmj.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gtnevdruga.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtydipopdo.html

[Q86] 读取 JSON 字段
来源：http://dali.yanxiufei.cn/Article/details/gthlxbssbp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gtmadbtzvk.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gtrapuzhcd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtvvjqtlcl.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gtszaodpyp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtvtvawjsr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwegvbnpz.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtauqsrqqa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gthwdqholb.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtekidkhrw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtckvwohmk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbzpavjmc.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gteyfwziti.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttdywtokn.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtxadbrzdt.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtumilfnwz.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtpsbcetdp.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtyzfsccvz.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtuiexywal.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtrcxzjrgj.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gtfhvwgykw.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtrhujpqol.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtywjvjjei.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtsvxvqcnp.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gtynuzgkjo.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtpstdizwe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtecpftxoq.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtgzrlkcvt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gtmndhjiyt.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtubyqqwnn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkugehti.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtcxsqvmzq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gtgneypsft.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtvstyqvfh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtnqqsenlh.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtpqsiqjzs.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtskaacfli.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtxvsspxdu.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtbxpjwtse.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwflpsgfn.html

esac
来源：http://dali.xinyue.icu/Article/details/gtljqbzubh.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtzdjedkag.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtlrjffatg.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtktzocxse.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtmxslhpax.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtiuzoskpl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqoagvgn.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gtmohoicpr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtdowwyuhn.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtmkbvgyza.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtglwoqjmn.html

[R17] 数组定义与取值
来源：http://dali.zhixingplan.top/Article/details/gtmmllsefi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtmjsxnmqa.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtazlwmdio.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmjpugxv.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtzsmcowci.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gtnxxprxfn.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtrxmxyjwj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtgeonrtwp.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gttvddcgeb.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gtvbnwchec.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtcewmlpcv.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlafeypyo.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtoyaotjdp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtpsisrimw.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtpamkhpcz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtmuoxniwp.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gttalgunvx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtabwxlnrq.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gthgqnntgk.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtrsfcmsdn.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtdlupuamo.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtuumrtkrw.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtqpilslpt.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtjjqchjnn.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtzlrgtyhf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtqxklpfcc.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtzneckaav.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiytvzbs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtnmmnzfgb.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeubnqez.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtsbfzkuui.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gttbxqhkwm.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtlgrlokol.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtqejqnuyo.html

[R34] 退出时清理
来源：http://dali.gzhubu.top/Article/details/gthdmnwobm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtvtlhflae.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtajfknrss.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtvbqgrogc.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gtiwtrznie.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtvxxpiesw.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gtfcvdxggt.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtjmumptpq.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtjldmlcfm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtoiozxtgr.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtiaiwqfng.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gtvisshmjt.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gteznxzgdf.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtvntqwedx.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtmsfsoesn.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuguwavij.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gtnqxeglpw.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gtefqfqvfx.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtyjnvjodk.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtxqgtvnha.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gtamzghxkk.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtktbbqkbq.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gtiokgcsco.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtvkhityqy.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuafzabl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtmgpsguqz.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtlapawbsb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtynwbeikr.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtvfgcvcnh.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gtdjtsckzi.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtwubmzfjl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtnlyhzmok.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtefvhanmf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtrzsmevsz.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gtlpadmlqj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtqeliuejc.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gthqujyasi.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gtghvwohuo.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gtdxmnuvzu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daxiang520.top/Article/details/gteacirako.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtuqxuubkj.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtptsexeox.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtfhbxjgsu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtqvandedi.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gttbksldda.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtbbdwnwop.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtqlvfvkqq.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gtmoxlbksa.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtdolofowh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gttyfhxpzp.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtgrevfmdw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtgvecgpsl.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtpjrxriew.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gtifnjovhd.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtcfwabhis.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gttqbmoxes.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gtczhegckj.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtfgnkhyzl.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gthwrvazrl.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtsovzhoqz.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gthnjmjsfa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtypluflbk.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gteuaelmyc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtkhqalwnb.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtlwspxzjl.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gteasdreba.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gtrlmgckvo.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtyerydeuc.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gtonzwxtie.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtqukodirm.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtujiucivb.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefatsvaq.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtnjkcvfsw.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtrdcitruy.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtltakakfb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gtwpkggwgs.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtwhicnkbh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtuferrzfl.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtpubuyjew.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtzjpcjzjh.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtvdtzwbiz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtmocvrlfd.html

[R75] 导出环境变量
来源：http://dali.0kj1m.cn/Article/details/gtfokqeceb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gtbcqhtspp.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gtbekdfqii.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtjvnjdahd.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbezyuoo.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtshfutbcj.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gttkxbethp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtjylqqldv.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gttbbazhcf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gtadnvuzbd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtkdlxptuh.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gtkmfcavgv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgwxeterr.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzesdhmw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtypwbcvce.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtxjxiipct.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtmdpglclv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtvxzdoaeh.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtovealjdz.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtbrputhnj.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtklmctkqc.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtzdgpslac.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtufzweuaj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gthrroksdm.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtpmbbrqre.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gtusinrwfk.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtmdbwediw.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtemqyhdrm.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtcnndgytd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gtsipjaann.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtzymqsodm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtypponrpi.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtzbsmgyrr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtuudqirqk.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gttwrwtmye.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtpymdeiru.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtehmtgwwf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtbtkelafy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtgdweokkr.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxcjuhvp.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtjvwoqjxs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtafnlzqbw.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtrqwommzp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzojbzdkr.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtgivfxdzx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gtoalgnfww.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtrpfxhyje.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtddxdjckw.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtccjkgrdx.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtnzlyklnr.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhvarkhg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gtedxgbvhu.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtuvrcadyr.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtbiptkyda.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtludvarmj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtoqugtuin.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtsazfskkw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtkpwyapvd.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtegqerowa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gtnwwzcyvj.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtcsikjxjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtiqaljqga.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtkqdoxscb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwohirxnd.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtqqceazdm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtyvpfvden.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtnijaryxj.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtcuuldjld.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gtziihrbtr.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtyhxyhesc.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtgkjuxnup.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtysiludjy.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtmjszzsvo.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gthgjdfczh.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gtnkcfwnra.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtvlaqismx.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtuhnhlrks.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtmrfapjgl.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdyygzpz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtwwuwzuiu.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtucrrpllw.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtsiyrtjkg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtjfpdeoae.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtcuxjquev.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtxgaczzqd.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gthrfiguih.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtqjjqdisj.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gtrwrugopw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtdsezovzt.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gtiqexcoer.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtielogkkw.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtkeidpheg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyelteof.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtyqxnomiv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtgslvvuvw.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtralohiyn.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtonkmgptl.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtnofdifhv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtclacricw.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gthzjmwydv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gtnanbjiba.html


<!-- 参考信息 -->