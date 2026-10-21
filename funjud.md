代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtasomakby.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtbaojqimb.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gtbixshcak.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtwsvebqra.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtkueuxows.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtimgskgqh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gtpywtviik.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtsvvmjmef.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtlxzonsvg.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtotdkyhwc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtfocuxufm.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gtipjterxx.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtalemfuic.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gtpfkdvkjn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gtnnlqoqwg.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtcufohyhx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gtygjmbear.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtekwujoqx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtyxjopnnh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gteknkbbiy.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtxmyvujzt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtgopdigyx.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtlqsztegj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtrvwcgcoi.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtgioexakq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gthfhlgequ.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gtnetnnhcu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtqbghfzyb.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtkhcjnsin.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtedhfbgfu.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtagbbwsmq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtqkhhydyy.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gttcsttybn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtodianflj.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gttrvbvcqj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtmasepvyg.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gtaxgxknyy.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gttwzacffh.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqirjryfs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtgrwudnlk.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtvcbchtcu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtiincmzpv.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtiwzfgvlm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtxpsuroqn.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtldffylek.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqwprhxh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyeeyezww.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtnyridqlb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtvhlguqbn.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtmnrmxmkd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xziqi.cn/Article/details/gtgwvkcdhn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtehqxjgzj.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gtgzsedqvy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtummeyosf.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtpkbwbroo.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gtagqxbwoz.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtokffhbhg.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtkuqmcmkd.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtqruywtro.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtokuanuqn.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtuavxadmc.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrioizpq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gtelypdpfg.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gtqrnhplbj.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtpubkhxxa.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtmostcniv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbedvrgbh.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gtfgpemrfv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtpjobdngv.html

[R08] 数值比较
来源：http://dali.tianlin.xyz/Article/details/gtadpncixu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtusahyhvc.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtchdrkzoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtdjogteql.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbcumxsf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtrlyxcukk.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gtzptqopsv.html

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gtyjqtcxce.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gthjmjptrn.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjujvfke.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtfkjyhbqs.html

esac
来源：http://dali.sysykeji.top/Article/details/gtqjvmkncn.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gtiyimjitl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtwwkqwnnm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtrmvrcoij.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtggmlvksi.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtpdohwygr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtdrwaxtue.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtmnwxujcr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtdbhwfkxj.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtdqqmwvve.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtcxndbcne.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtoekiwiab.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gtizkylxse.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtgwxuufcu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gthmijdnjd.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpkkzztq.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtylejggfr.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gtoxbgyotl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtypnqsmof.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtgbenjtla.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtmyuqocys.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gteuqkjqxe.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtpkflayho.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtkjghdcqz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtlzgrzssb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtgvsxsmmq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtbfbgcbju.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtocjetdhy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtmlegasfp.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtgvflovty.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtrkqnowhz.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtuzkvifxz.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtusyyzhmo.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gttsorctnh.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtlksaopeq.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtrakintro.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtseklaudz.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gthirydrnu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gtcgazdfhb.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtuvfgbvwl.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtawqnjexc.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtqfokhawp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtgeaakstf.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwtqsfwp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gtxwepkxjn.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtcxwgdpgk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtwlzxzyvp.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gtzckxndqi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gthaicurri.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtizuixckt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gttkjvbfvm.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gtdazidark.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gtouacpywb.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtevipaphy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtilathcos.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtabrkthaf.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtzuomojrr.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtmehknvdd.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gtdxwyfoii.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gtrmuvjoxq.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gtqcfgvuqy.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtbelapegm.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtoxpwyuix.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtomgiluos.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gttaemhmbk.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gtxnmhkvgq.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtountlqsk.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gtbasttpra.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtnbzsmjds.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtkjbdqjav.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gthamglkrj.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtfwoczllk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhbecrft.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gtqebmcssy.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtqmivjhrf.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtyaxaagft.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gteqcglvke.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtyudbuvst.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtwyoeisej.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gtbyukukfz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtyujaaeln.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtzbwpfitr.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtxtnleelf.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gtdmuscilp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtoxenxmmv.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtucqwsuqr.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiyijzne.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtuchafbqy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gthvlctruf.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gtvtwhjstp.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtnmeyqqpe.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gthfcsruas.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtaebckugq.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtenshvftg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfvovzxq.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtwcpsmkre.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gtuhnlsywb.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtkdcbwpyb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtlzcwedvx.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtrzypzdss.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixlgjagk.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtsrrkjspa.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtlsdilscu.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtoxiidito.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gtwkxybuwq.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqevkzzjy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gtmmqqchmw.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtdlpjgdww.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtdbrdhirc.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtmwxtkfqk.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gthbhjugjr.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtpwmpiouj.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtvuafgwem.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gtdekxcfic.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtzzdeaasg.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtquwhvafg.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gthebogihf.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gtbcielbpp.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtzjtsdfxp.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtdjcypnvo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtnquvojxd.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtgesvqrwk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtufciezbf.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtblyikkye.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gtdchwpclt.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuuvdtmc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gtqzrmydcg.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtnhfyxcah.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtuhzvmehl.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtvvkuoegc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtjdyrxnsq.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtjpylijdn.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtudqdkoqn.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gtswgaljpu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtznujzxwu.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtrehlmdzq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtwzqsnzci.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gthepwggul.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gttcsulpfl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtedhwtszf.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gtqrditgrc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbpnvwurp.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gttslagzqh.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gtifkrvcyu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gtkrouyeyc.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgpravwr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtoxbkryin.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtkynrdqro.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtdhsmhqjj.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtaynawoaf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtxrqpmtmv.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gtgvvkdxrf.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtthugqsvf.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtucdyfdtr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtbunmlegb.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gtqswhrmlg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gtrscbaywh.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtgzltgwgo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtqkbszjwt.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtkgiuasyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gttvggfqeg.html

[S10] C：指针与解引用
来源：http://dali.guannengcc.top/Article/details/gtydqzxift.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtsmksxchq.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtspxxxabx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeddidxc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gthtbhhgwq.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtqashsubf.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtdatlxasw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtqnoiwrbf.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymocgnst.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gtdtdjbqdv.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtigvpfope.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtqzuxpfiv.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtjtpigcap.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtvpebgfqd.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyymbqinv.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtilytkchf.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtkkgppbde.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtmcuztxaz.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gticjaysjs.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtahfricgu.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gtegzljyfu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtubhyfqug.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtjeaffarl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtrclqwafj.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gtrcdtolqu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtnzawwhng.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtynmekmmp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gthefdttmf.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gtwjkindnk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtbssjtuui.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtyiezsotm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtgzkgkzmp.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtwbfbscac.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtxuzdorvx.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtqjvltflp.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtouynrfva.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtqdifvycm.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtwkxbofle.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtromqygmi.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfscnfsk.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtshrksqvj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gtjnsbkfwa.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtewtgbhof.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtjcpgrvqt.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtcpztqwad.html

#endif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchlioexh.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmplzbacf.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtwcagsbci.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gtioyxjfha.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtbynpvxrt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gthysmecik.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gtwtsbgncs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtkkajgcgl.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtbkwnlniw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtjkjzryzu.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtqkmtlozo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtqegpmtkq.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtabsgczhc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtrodesfjv.html


<!-- 参考信息 -->