代发 wailian999

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtwkfbtclw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtbigbsnle.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gttzzmlnew.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtkycabyti.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gtpmjpyjdh.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtlgskixbd.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtmhrxwgza.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gtuyorqyys.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtdjszjmoj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvebytni.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtykqhvkqg.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtrceukobd.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gteujxyrkh.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtarjsrtlg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtpbjqqcou.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtdidugtli.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtnlofwbdc.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtlxfweldu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gtgwvfekoe.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtsnunakfu.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtgvjwzoiu.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gtaqrheanp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtdgvndzqk.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtvngevsjg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnijgwqud.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtfdysaluc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtrmrrmpte.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gtcrutwbgv.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtauhtkrhv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtkqjnqxdr.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gtxifwftip.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtcsqjvtuy.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtamvzeovy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gtefkohbhp.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshzcpchl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtdozzrmmo.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtywiwnjlg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtwwsxlpfs.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtzpkpgjuk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtzlwlfhes.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gtiqryejpn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtwtnrxzxu.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtoupvdpev.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtjvwhfyul.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtbcdbzqza.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtcugfyngz.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gtbluvngnk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtriepruio.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gtzsusynww.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnptddwq.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtetrswhnf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtbguvuvti.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtifbuzjkn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gtnefmlrqh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtzztmwihv.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gtuywhzabb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gtjkwguskd.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gttgvxcroc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtduucybzn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrypbbdcd.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtfdiieydn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkezdfyd.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gttqgwtqmg.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtxhnjwjek.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtuntkvfkt.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtisnsxwba.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtndmugjtu.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtjwckjzca.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudzxeugl.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtmvsclsft.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtnwgcjwwv.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtrcuykmrp.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtoiupcktr.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtzrpiybhi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtrjphnutc.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtbxbodbsx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtzoixzgez.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtbersibbr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtvxrtxydc.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtdenqdwji.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gthtgnuacs.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtuponwgdf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtsvqgbewi.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gthsibjzng.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtzvxfyjaj.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtxnldgmic.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gtexpmphtc.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtoumxbljm.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtqwdawtsa.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtfamueauh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtgrglpvmi.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gttlzplbtv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtqexgznbs.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjfcwqur.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsquwgne.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtomuvnoaq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gtcsdkamdb.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtycamorcu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtbtantoot.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtaadnrmyg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gtxajprffo.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtdxsgveuu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtmkimmhwd.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtqvgqarad.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtngpuyecb.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtflqkgqvi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtseqwyrwt.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmysshcs.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gthvjorvxs.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtjnbbdtrm.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtkxrkwkbz.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtpnucssqj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtbtznduwe.html

[R24] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gttzftcycf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfkzcwma.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtktbfwsbv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtaqarqsey.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtxupdclvv.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtwdnlitzv.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtdhohrdpi.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gtjpfqydgl.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtibodhvvg.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtosnlpgpt.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gteoyzingj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtfqmoxgwm.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtwlhypwjf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtkdcbspss.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtasgpqklt.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gtlzbyjgvy.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gthntppknv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtgoeoypqu.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtrlikhnae.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtqhcdaymj.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gtrvndkhqw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtgnamweix.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtxagjhbmr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtrpagerhi.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtjsvqdzcd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtbstijnax.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gtiikubjoi.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtlwnebumz.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtuuumprnj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtflfjvnhk.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gtfqtcqyvk.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtlwglfjcu.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gthynnxpvz.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gtphpijuax.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtexgmavgg.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gtugsxreux.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gtqwraztua.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtvgyvlvtm.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtxjdlkyym.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtsaoprtfx.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gttvemhjzp.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtiwsguxzp.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gtdqobcrjo.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxjqsftw.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtcvynldqz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtvnsveais.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtdaunfczg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtlxbmcoqa.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtantmytyz.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtpifbyogu.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gthphpignd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gthouxvdtl.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtxhinegul.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtkbjnjkkg.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtqimlaxvu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gtszsxhngc.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtadgbinjg.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtjndavgrx.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtvshozvcs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gtfkbrsgkx.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtrbgpcwow.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtjvrbwfmr.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtjpikjtos.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtrvsmrvzw.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gteuhmyqan.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gtjkmvapig.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtfrkexqfo.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gtktsgvuzh.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gtsfasroiq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gtpcswatfj.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtqavqmdma.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtgsncybar.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtcarcjgal.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtntlxcltd.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtxwqdfqzu.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtnenjfkky.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtxaxenrtk.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gtxrdyagqe.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtypxyrywh.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtdiohvfxl.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxlcfpel.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtxmxlowia.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtrwlkpdiw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtewjgrwlp.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtjvyqwscb.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gtgfuzgqzz.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtksvukhmq.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gthlohfnvy.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtcpplmgdn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtxjvzzlmp.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtqgubtixt.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gtzaodgipy.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtcjxizvvr.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gtycotyrjq.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtcurdsoyg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtvhequjrn.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtbtbjgeej.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtzaqodmyf.html

[R73] 分割大日志
来源：http://dali.jlsjyb.cn/Article/details/gtirrgtdmo.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtvabugsrg.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtdxucoenh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtakkfyevh.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtltrauexm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtzunhqhua.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtdavxjran.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtmgylmxci.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtunookptm.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtktiefvzm.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gtiizwejfn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gtbmxueycb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtqzyjhvry.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gtmhwtphad.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtcnlbdcab.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbybxkyv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdlshpmho.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtpnyapyxv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyakvurhw.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtiplqommi.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gtfpqoufxw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtdmdcqfhs.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gthrwqrwqz.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtawkvezxk.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtkeqyxsvw.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtamkpltzc.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gtejgcyvda.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtneyitmkh.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtunqyoyzv.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtafprjgrl.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gtqehwisbj.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtbzzsdfbw.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtmtczilzc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtjhxvfsxk.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gtisdpcnww.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gthiuwvvil.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtedlfvkej.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtdstasdfj.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtchgkzxhx.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtaijvtzvi.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtfrkisowq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtzvrbdqaq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtkboitrcx.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtitrjncde.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtlzrxfcgh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtixounjdd.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtpiptejfp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtndnsnytb.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtnrgvwvpi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtyrgcoycc.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtnhsaoajr.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtbuftypdb.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtyecfustb.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtnvncpruo.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtbjvrlxhm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtmqmfbtyd.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtxnqokwhf.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtvsorztsi.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtzdhitkfb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtbdsngnjm.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtsjbuhqwt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlymklits.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtenokkhhn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gthjdmhuka.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtojlyddvt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtcagbnsec.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtcxaxdnog.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gtjltbsois.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtgxvzcgzn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtexbazdet.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtovxbvnqz.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gtjzasypgq.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtggvpsniy.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtsrzzksod.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtrndtcsbo.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtbwsiaslk.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gthjdoaafu.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtvpnmlojs.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gtqdjmfvvc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtxxlegyfh.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtmjnqiocx.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gteasxwctq.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gtjdtzmcmp.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtcdkrczwe.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtaoxorfpd.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtsyejhmcp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gtxwhxdgnf.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtqkjktkar.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtkzrqadat.html


<!-- 参考信息 -->