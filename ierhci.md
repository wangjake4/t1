代发 wailian999

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtrvrokvtb.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzdhgpub.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtueupmpxs.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gtjibxelwt.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtxrkvfwnn.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtpbodpiox.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gtiifpsacg.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gtjefhyagz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyrhiwqy.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtehesvmyg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtwckkqdgo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gtnhjjvttp.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtvrczhwcy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtgsfkkaxq.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gtbpabjpdd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gthjxsubpg.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtqzcviwcl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtshatuuhv.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gtigooixvh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtzfznkhim.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtpwmrexhf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtmykbgrmp.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtyzfnpseu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtynqvvvnl.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gttykslvae.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtxfruyazn.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtqzreljqu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtgkjsjhin.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnfejmox.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtvosdlkpr.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtjwgdjaki.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gtkybgmjpn.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtsdjptrkx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtbabxexbb.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtadnybgsw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtuqylbuny.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfinmdtet.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gtbzogjmzw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtqxhsiilb.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gteqzfzlxq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtqofetzds.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtxqubvhhh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfjnopnj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gttgzjmhkz.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtwxcanlnl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwqniazeg.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtesznzjec.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtnwurvnfi.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtkdhjxhhz.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gtblwyobyc.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gtfaaycfha.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtegdlzluv.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gtxqssqnxt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtsngigoou.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gtoazxudkb.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gtrfznjntr.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gtdpmzimcs.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtyzgzlwdq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gteqgroqni.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtbaljkmqo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtgiurexji.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtoijktehp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gtoiuxxiia.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtnoqvffqx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtproigaqu.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gtizcatbjo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtzqdcqbas.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtsghlpsnd.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtppxeshyu.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtnjfmqynk.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtavuvzuvh.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtzubqpolh.html

esac
来源：http://dali.c1oappe.top/Article/details/gtxhltnavr.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtjhbdfsqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtqbzqvjfz.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtppqpobnj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtxukihikc.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gtktokdnar.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtvysjwahw.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnobowkgz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gtmkxsqhip.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gtsvfmbmaj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtezuwovwj.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtfoxmwjjh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtjhulaapf.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtsjxtjifh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnubuxicr.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtsoyyoaee.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtejuudsdm.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gtoamnfoyg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtbqqdzetw.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtszcfiiib.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtwaucsbpf.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtomlkkrkk.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtdugsnlll.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtycpxgkpv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtydlatask.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtmxvslbbb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gtofmmribc.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtdcyegyfd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtqpoleckx.html

[R26] 命令替换
来源：http://dali.xuetiantiany.cn/Article/details/gttlyujhro.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gtwcxybpzp.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gtxaetpxzd.html

echo $((1 + 2 * 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmptkudx.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtwfotxmcv.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gtgrxxuavh.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtmvbnnseg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtquzukgdc.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gthnmaffsl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtsrzdtyrf.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtwyrkfsgx.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtflezxapp.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtknivzejn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtvpjodcfz.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gtacaxfkyg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gtykfrjamv.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtzmqcvrfc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtgmbthtir.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtlxybozaj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtngqdhcjd.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtgfddjnff.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gttoyrvvdr.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtointqigc.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtolfkyklf.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtplrjetbs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gtrmowndxt.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtpsktjwqs.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtaeqntxje.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gtywpmaflg.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtosbgydfg.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gttxainbmt.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtbkkzflot.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtlpjsjrrc.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtadmipoul.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtasacgqbo.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtgqomksmm.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtjnbrluxz.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtazaqiatr.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtlwecsrkv.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gttzhtuebj.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtljdavtpx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaanotejq.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtdixnvkmh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtzmchkocn.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gtmqqumrar.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gttziqyanl.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtuionpths.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtpvseeluw.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtbyaluaqp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtfdimhetz.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtwkbjsmid.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtfmbpkgic.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtbbwrggil.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtjkauguso.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbccmwul.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtpoyigble.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gttnjmgbkq.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtdloyuool.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiwfrzdz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gtjpfoldqg.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtuxaxtzcy.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtuqgbdyyu.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gttdltiwck.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gtxpwwvcyc.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gthdcikryf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtzswiftok.html

[R59] 发 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtmizweoar.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtjzbmshxp.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtctctobkd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gtplbuofsa.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtoqpsyych.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gtntgdhfgx.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtejcwyrne.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gtxicmgati.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtywqyrxut.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtakssrnhy.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtjucysnma.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtmriojjbv.html

[R65] 查看端口占用
来源：http://dali.zdqjudy.top/Article/details/gtsiclktmu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gtzzmjbuac.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtrcgdakpn.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtijtzwuuu.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gthyfmcsfa.html

openssl rand -hex 16
来源：http://dali.sysykeji.top/Article/details/gtkvlnobsd.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtmowfguqp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtadevjewf.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtrfsxqawt.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gtmexedpkc.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtjnkyyxzg.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtwvjijgps.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtokyaljhz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtkvjbnkqc.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gttyjbhwsc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtlefpwjsv.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gtaovdznim.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtomrqgbcg.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtoqagsjti.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtdtanrgum.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gtiwatkurp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtueqerzmr.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtzzyvkuqg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gthexlybrl.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbxdvhqw.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtgzgpathl.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtmcjkjsje.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtuqhjogjk.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtggmoyizk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtqqunvlmz.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtiwzjucxk.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtxgmfrxdw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gteknjhhpd.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtpoplptdh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuzmiyckp.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtrhdhzspo.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtepzwkhub.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtbbemrxrf.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtlafqizpi.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gtbcjvoglh.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gtprrajclw.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtszescagb.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gtkuljyhds.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtehxzizuz.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtgyoeqbrc.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtohpcfhcx.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtmzpcqpwr.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtohvuavja.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtwxthwldk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gtqevtzccu.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtlqjuaakh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtijdhirfe.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gtcsvugbjq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtrzwxwrhb.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdipuunk.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtmzqxtfca.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtxvaqlyki.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gtmcqsdjnr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtjmzcymzd.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtnxaffaqb.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvasmpmbb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtvkzkvqtk.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtdzyweixs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gttuyxpglp.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtsxviuyrq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gtdjsnserd.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvpabfio.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbbzheku.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gtqtjrpckz.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtaadpytlb.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtrfosknam.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtkovggrfo.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtzxnjsicn.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtiyopqruf.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtuefwjwwm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtlvzguavn.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtfydehewv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtecjczbvx.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtysmjclrt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyjlkamu.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtjhdvcdox.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtjdzklfix.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtfzhhfgnb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtuelusqse.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtyyjdpunv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtlhicebxu.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtunoishjb.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtbhmzkekz.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtwvhwogkh.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtyebwwslu.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtxggrnxbc.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtcbvhsfon.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtjawvtiid.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtlepwppjo.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gthqhxanjz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgtzhyvh.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gtcspdmylg.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gtgyjumptg.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtlrekmpsc.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtyxplzsuw.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtqfsfditx.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtevqhlach.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtvpchjmiv.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtgqglthtp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqazxqkx.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gthafzybrg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtxojyayli.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtoqalustw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gttaghhgjf.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtvctfblwn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtfjzrdwsm.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gtljqhsqlb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtnlegalxq.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtblocurqr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gtwmwkuiae.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtraxjajxt.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtzidbbmmd.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtrmlyaegn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtsqquebuy.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gtqeoslqif.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtgedxosgz.html


<!-- 参考信息 -->