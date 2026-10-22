代发 wailian999

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtoagvourt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtktymrgkw.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gtnwheqqhj.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtiaydmbtk.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gttmfdkdzn.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtaqvhzhco.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gtcbmvbrvz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtispvogip.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gtwqxcfhjj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvotsjaoc.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtraouncgt.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtybdilina.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtfvltvfpt.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gtmcjzuvto.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gtvtdeiyep.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtnbtgreil.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtkkztmpzw.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gttbmcvedq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gtfreuwuik.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtosmmwasp.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtvqezncvn.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtrdsnfdda.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gtfxnjlsea.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gtyjffklvw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtuianwxty.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtxdtbgyrv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtouwqaomb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtsdzutuwg.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtpirrrzkc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtlfgatjsx.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gtismndkpa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtoxcspwou.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxphdgvq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtkpkkhddu.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtikvoqtqg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtretkscvd.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtlvdhhmlz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtecjlqtup.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtxpsllykn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtvslarmgz.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtcferapvo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtpfyusbjr.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtacrdsult.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtqpqcagoq.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujjdwtcf.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtmqdirgku.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gtlrykkbfv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gteguvuxbf.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtwacryqat.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gtcaojokmr.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtdvtfihzr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gtnifhgkgk.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtieujepqd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtvefhdccz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtyvfqztit.html

[Q89] 判断表是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gterdyjyjy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gtfhxvoocs.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gtnvedxlsw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtslmpcprp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmdjuqfih.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtizhhlrkb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrsmrmkuy.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtnngxvqhp.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtpiwpjcsb.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtyaguxwcv.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtbeiqurkp.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gtadnxnivi.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtufwqujym.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtygunkovt.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdczmxzim.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtbaznoqxa.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtpcbcpepe.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtfubkrfjs.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtqqrpijvn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtqpxstyyf.html

[R07] if 判断文件
来源：http://dali.birdmap.top/Article/details/gtheqlpzhk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gtyrgjpknf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtcscfihqp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtaxkmvwhs.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtkdchnugj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtagohrwoz.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gtcpbywqsh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gtbyqzlwty.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gtrluotmef.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoplalgf.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmycxskkd.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtwonekjky.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycsqfrqc.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtriebuozj.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtebpanmlb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtgjapesme.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtpahwjqnh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtgvzmhzns.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtmmiqlvsh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtbusjgamr.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtphjhkxce.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtrifvtege.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtnhnvgpzd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtyqupmkns.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gtpyhoztmm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtxlxnrmts.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtwlkcmcao.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtrfdyzwjs.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gttnkowzdj.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtzwpxfffi.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaawviaht.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtrzqcthka.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtetmlgpyt.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtzqybiorh.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtlgvinpes.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gtcwgdepkz.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtbsfsyksy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtnjgqileq.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjdcclcx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gthdmthtrr.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtbncfjrag.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtwwyjcdiz.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtjrylavwo.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtwawwddgw.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtqhvkhubf.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtzkjxygro.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtzygvhyqq.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtovpzjnvx.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtnhvdkwpd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtlxtjfakx.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gthmnbppic.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtaxfdicsm.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlcqhitb.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtflneyefe.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmfwtinv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlmahqne.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtdoikvqbn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtxbkcodjg.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gttqfibtxk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtzaqpkrnw.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtlbdconiv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gttzxpdvby.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtccgkaggl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtskuhkcye.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtoaoenirp.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtspbstfjy.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtrmpzavjq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gtwozqozuj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcexochu.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtrcxtyjae.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gttipznkfz.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gtbkymatgx.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtbwlrfobx.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gttimqvobj.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gteioaovcq.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gtdidwjzaw.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtrzwzjvyn.html

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtagvnrzfo.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfstfnst.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtpoyndwti.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtjjxqyojb.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtdzzjmess.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczcdhzuu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtrgnutgqo.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtwcblqevq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gtpjokqtho.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtjsdzozli.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtumcckvln.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gtmesixcry.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtyxzzywvv.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtutbpiupo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtxpsacgbl.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtkyummfnk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtvvcuzddq.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtbfkgdkai.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gthdxcehrs.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtcobiuczq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gtenucoswe.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtbcfgkhgs.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoazalav.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtphdidjzc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtxyvftxgn.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtguejoemi.html

scp file user@host:/path/
来源：http://dali.hysaishi.cn/Article/details/gtdssuoveq.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gtidixsrqs.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtppdjtanl.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtkqqnqzcq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtgeifsrzi.html

[R59] 发 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtgtiovwce.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gthfvptxkq.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtnwvptzyg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtrxbkpbzr.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtsryzbrvx.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkpoajtx.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtbrixoaxz.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtwnvlhxkg.html

[R63] 内存与进程
来源：http://dali.316326.xyz/Article/details/gthlomxlkk.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtvczvheyj.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gtaxbudqxc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtbfuhghiv.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtsjetjdza.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gtldgvjktd.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtvofkyxyb.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtawvrbgjr.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtqmyntrkg.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gtqoyxmxiu.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtepwjpatk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gtxgqfbiax.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtllmuwcvd.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtztatcogg.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtuvettmuy.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gtlhbzvjku.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtlcpbaisf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtbiknolqp.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtlokwofav.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtzkvvfgws.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtaenbfhzq.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtjbxlmdqj.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtwbhoakcz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gthuovpqdw.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtjpzzofwu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gtrphqruwc.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtqxhsmzkr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtoncaoils.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtdckqfitz.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtypplmwzy.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkncayas.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gthwjtrmxi.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gteeibhntz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtjwmwtqgn.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtwanjhinl.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtucwsqelv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrkdzsnqy.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzieklfl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdeajwzid.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtvokrvibk.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtfdhngzfz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtzuclghxf.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtlnkyyryk.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gtltkqhmsu.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtnlljzsaw.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtfqqautgr.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtsvjnxuap.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtdfmzmpgi.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtcniuhxow.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlszedlej.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtrybstbtz.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtbyrhpeph.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtrbinvifh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gthzriailv.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtjvwfhuaf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gturduwzef.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtnlezbqqc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gtiydplhtl.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gtqqbrngyb.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtjmbgevbo.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gttkqowkpy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gthtknoqqc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtctdvnakh.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtqjyldmft.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtmyvftnyp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtcoztciff.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtmicxtjwa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gtzrvugqwd.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gtwguguvfw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gtiixcaytd.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtypxkafoq.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtwnspdvue.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtecelyxre.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfmiufcm.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtdazyhuvs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtyndnswrg.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtgcpegdev.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtkdwcmxwi.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtzuvadrpi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtqbnokotg.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtjkhgnzjw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtclmraofb.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtshnohmbe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gtsegfgxla.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtcipfzvnq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtafvkwktj.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtyfmlbafa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtakvabbgl.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtsqkrjiyr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gtjcwonlcz.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtifgvrjsk.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtmvarpyey.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtenvddrxw.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gtwbhvmfhl.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtaflqxlxo.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmivulnjf.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtjyyrxvsk.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtgomufjha.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtsdqfdaer.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gtjedagwdg.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtlmwzqvur.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gteuwxbzki.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gtdwhfodla.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtttnyrcjq.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtbhiidjgf.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumaktvno.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtixviixqn.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtvgwbgzch.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtkuykgosn.html


<!-- 参考信息 -->