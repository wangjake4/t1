代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gt2hzrtneaa.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zowsgequ.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2yfdvilwc.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gt2uaytnskf.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gt2oekreigc.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gt2amuiewfq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gt2kawawlbu.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gt2kxtvvdub.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2ahiuiipi.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2odeenluh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2batfcapl.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hroselvf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shangyingyoupin.top/Article/details/gt2blsutqgl.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2cbatglay.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2nquvqvrb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhivbysi.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gt2cmxdwisc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2kqlqpixw.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2zcttaari.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gt2simsahkq.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2jniabvop.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gt2haywvnqu.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bktkdrob.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gt2bcwsjgab.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvqwbefd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2mgvfdibn.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gt2ijzvawxq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2nvqxldoa.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gt2jizgtrmz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2oiewukmh.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gt2lrrjwexp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2adzncvlc.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gt2ntizarhd.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2vzregdrn.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2mywqahrd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gt2xpmchase.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skdclflk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gt2xeasnmqv.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gt2qmaqvxla.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhongyouzk.top/Article/details/gt2oyydjuag.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gt2pzksqnoh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gt2bzywintm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2mxeftfgt.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2nxtfsszo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gt2kyzhjhbt.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gt2purxtzeu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gt2qrnzytpv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2oqkatbpn.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gt2ulcbsjjz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2snjfezlo.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gt2sozvfkci.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gt2fccnbvxz.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gt2wliokuyw.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gt2abeocuom.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gt2rkilenjo.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gt2oezvyvox.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gt2laxkcwca.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gt2tfzekmne.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gt2xglcfkxk.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gt2uaxbnrpb.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gt2xaalwhji.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2rjohcgne.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gt2kvuffgbq.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gt2luhpxfgv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gt2qlsykfft.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gt2iodonrls.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2gihlmgzy.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2mieonpjz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2igkdwszm.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtqbetpx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2kaminlyg.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gt2iavbxyvc.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdhxzvnp.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gt2gcdhuaen.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2tiyekdgq.html

*)     echo "未知命令" ;;
来源：http://dali.xuanzx.com/Article/details/gt2dlykeikj.html

esac
来源：http://dali.jinqigufen.top/Article/details/gt2olraagyx.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gt2btzejxca.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gt2srxnblbb.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2hwghwhmo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2unwompnz.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gt2jyvdviza.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2zsxlkpzw.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2smjwecbl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gt2mgzkveqa.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gt2bpjfdivu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gt2wdmjpkdz.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcbwpkap.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2ntrnbvnn.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gt2zwtiecke.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gt2rwfkirmj.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2eigbhmtb.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2kyllarmp.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gt2qopfzdte.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gt2wyeoybsu.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuiganki.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gt2ohmykkfu.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gt2nrsyavtp.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gt2iujgtcoh.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2zyulclsp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gt2wycyaaqj.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2ncxkpxcf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2evgngptn.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gt2gcirzggo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gt2wxvduqee.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gt2ihxseszp.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gt2prsnbpor.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2ejisvify.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okkskbbp.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gt2zefvhtkv.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gt2hgkleafw.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiiffsmk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gt2pxgdsynn.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2byyliork.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2ixcryksu.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2zejyfgmq.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcgzasku.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gt2ntgyurge.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjvsrgkk.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gt2nyhgaxoz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gt2dockjhfk.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gt2txvimvtr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2aeefejde.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2tpzpdsnh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gt2bamxialx.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzctsvug.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gt2xqddbklz.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gt2nhoqfvkt.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2txdlrowq.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gt2bekfmhln.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gt2dicnxnjy.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gt2floschqu.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2vadcfnfh.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gt2wtrvsnzx.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gt2vlrlqhlk.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gt2pmffeccw.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2ploebood.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gt2yrdbotvf.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2mdzxsdpm.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gt2soivjbxz.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gt2imrhupnf.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2fdkuhsca.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gt2szdfwnsj.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gt2ggpiuvtn.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gt2urfqfhkt.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2kjhdqcic.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odusciiz.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2crwphubq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2qopimxzo.html

[R48] awk 取指定列
来源：http://dali.jqgufenzy.top/Article/details/gt2jjvositx.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2ujyizzoc.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gt2fevmylbk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2qqaxkpej.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gt2bnjedzbv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2xmbadbus.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2bqxvlcub.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gt2rojjbexu.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gt2wpqzdjii.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gt2guwwxnex.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2godicrip.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2atmxoaxf.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2hmzkcxoz.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2hbpkkhub.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gt2hjumbfjx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2rcjiuyyf.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2pblgwcig.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2mcdqtnud.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpgmkxfa.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gt2crdhjjdj.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gt2ntqsurwp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gt2kzlpdsdx.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2zbftzies.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gt2tcnhntgw.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2goixdmvv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gt2eibotdnk.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gt2hmwcguhn.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2tntowbkq.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gt2dfkuqxvo.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgrfqjas.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gt2bbehhuhl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gt2cgpostzx.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gt2dupmdjhn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gt2catlrwig.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gt2oypjvtun.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2xdsgxnbp.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gt2gddoxutt.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gt2ozzksrlj.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gt2puptjmup.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gt2aprnkszg.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gt2knvhwovz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2chwilzna.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gt2eewdgsmq.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gt2plgyrbfn.html

[R70] 时间戳与互转
来源：http://dali.dianchejie.cn/Article/details/gt2imfxsdvc.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gt2hyiwqgbw.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2mupybxzf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alsuiqgt.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gt2cdobimqc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2cpcbsppf.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsfwqjkc.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2fhfovago.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2hzxcroxc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2gzowvbuh.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2qpesjqwo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gt2dgydlfdd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvugouaz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gt2denhdtoy.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gt2cnbugewc.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gt2qwwrytad.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bubfegzo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2uotehuuu.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2kpxnbfxc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gt2glglxfai.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gt2pewvgeyh.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gt2kdfizzuo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2lreafsye.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gt2qznobxgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tayjpkbj.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2jwijeniz.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gt2xiygqszc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zugbcrau.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2egnudmev.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gt2dnqkatpn.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gt2nxdfqfep.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2yymxwatd.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gt2eunrjxio.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2iejnrhah.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2gocmpfnt.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gt2sjhuwthq.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2dcgouiep.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2fiukuwwp.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gt2unvrybqa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gt2cggbxsje.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2valelgwa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gt2jjdvopfk.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gt2vmggtsco.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gt2uzigndqi.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gt2auuwmind.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qegzazhg.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2oytfspwz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gt2jjqlslos.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gt2wbpmdzzg.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2sbyuguvt.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2znqpvhqi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2wsiffelz.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gt2fdbahycj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gt2uqwatcxb.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gt2rzyksjgy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gt2fmgdqufg.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2jakrdsjd.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2ymjdkjem.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gt2uqkhjvsu.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gt2getkqjfk.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2zrcjmkkh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2ixrntuod.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2ghprmrxr.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gt2gohsvxtf.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gt2kitwelgf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2fruevlyt.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gt2ehajitzt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2tanwueiu.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gt2fcycpqew.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gt2modkqoih.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2kwcrnjcm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2stdzalhu.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2tqmdwsii.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gt2fgdskvdl.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gt2ymxvvvfi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gt2hhybcswk.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2viktqyhc.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gt2cdhilnfa.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyuxjrkq.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gt2lfhljmuo.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aguvusgb.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2gdiifavf.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gt2mbxseddj.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gt2sahekdpa.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gt2dyrdonxn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gt2rcvbuqdt.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2fvcjhsza.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gt2gjdmzuzo.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gt2mevkdyus.html

#endif
来源：http://dali.yj202588.top/Article/details/gt2fxjqthwi.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2aqmvybyk.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gt2wouuqdjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gt2hteowahs.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gt2dqanjgbk.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gt2pnkiljlw.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2eollrpuj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gt2xietphca.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gt2nljcltjd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gt2xpivjddz.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gt2gcmibfml.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2wczinzfh.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkilbulu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2blilaflv.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzdhcvci.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gt2jxmiclvg.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gt2hwqblccj.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gt2lqounhld.html


<!-- 参考信息 -->