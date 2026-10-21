代发 wailian999

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtkafsemmt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtqhubcmlx.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gtgiapbyxk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnetlprk.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtzzhvorwa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtawakuxyn.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gttotbfzvs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtzzxgkcbw.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gtrdzyubeu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtayzvcvpl.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtruvsgnmg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gttupvzztt.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gtasqvkgsh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtjwqkizte.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtqehpvjpt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtyldyfxyi.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtharngbei.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtcpgsvcfw.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmprzilsu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtadbplwgn.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtrqdmihim.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtnorbjiqe.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gthbvfizep.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtxwwtalfs.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtlfigiaku.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtiejvgyri.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtnlycvchi.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtmldndvei.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtyrbbnxyv.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtzntpegch.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtcgubklhs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbcoczpym.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtaiuixogk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjhgpsozm.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gtqxlogkpc.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtyjnacihy.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtniuqlghf.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtszaehdim.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtvxeawscc.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gthtgatfei.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtuwfmpcky.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gtfswuxnup.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gttzgkrmpn.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtcfsnvkos.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtlabdlacj.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtrzvimyjp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtybxtgtbv.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtmvpbitja.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtyywywzrh.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmzafztj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsnmcjrj.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtqjivvrjx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxrtdmyf.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtsuyllhwj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtbtiwnzki.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gtqvgljhjg.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtdhsodvxq.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtuiwvhcfm.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtoxyekceh.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtintnrrgv.html

esac
来源：http://dali.sweek.top/Article/details/gtvtlqfhek.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gtycbhefva.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtqrwojjyo.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtzeqrqnkd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtwtwlnzlf.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtwknnnypi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtrdrvwdwg.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrezaoxdx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtvftdlsrk.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtajngukdh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gtxfytgbrw.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gtwbeulugj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtpswgksgm.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtjbcxwkfu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtnnutdogl.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtdsiyobbd.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtzelxqmas.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtlbcgknbl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gthmogjfir.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtllfryrnu.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxhmiliw.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtifarroha.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtgdumsekm.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtntsjwqpv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gtykrplppc.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtscbaqutk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtmmkryvms.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmximxiit.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtsqiinitb.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtdqutltjp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtuweaihtl.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gthafcocdh.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtxipmxbpg.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gtudgmacrt.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtfyludrcx.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtishyezns.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtppzzrmor.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtubaitukv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtobaqyxvk.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtbaofqgig.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gtywbhqhgz.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtkzosqtko.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtrcxbeaxr.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gtvycgnmxn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtdekxjeir.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gtexlksizq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtzbotodvq.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtlgazgshu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gtynnfaope.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtmwxcimgu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtoiogtdnt.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtyrlrawml.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gtwxgbmgve.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gtggxtnqkt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtvevzmlrv.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtsopteeuj.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gtutpstzyj.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtmejnabwa.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtmfflmesp.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gtmbdgqbiy.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtubseenaq.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtujedrrwu.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklivdjpw.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gtsuyhtqqp.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqxacgdq.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gtxknfbcig.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtqughtlyx.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtcciwssia.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtgewcouri.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcwpyris.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtodgkwyqi.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gtadqhvxho.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgadqqhct.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtiauznuvl.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtggqnzrnx.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gtifaecmdh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtoiealogq.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtefqekevc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtombejecf.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvfxhsjr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtlgnapxiz.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gtgonjywef.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gtgrhaqmtw.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gtowjvzujc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtmdpkyhcp.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtivrgppxj.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbbyppbl.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtghojcszl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtxyjusnmu.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtswlxgips.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtihcjzwre.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtzonzvuwf.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtwynvqcki.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtcnvunxkw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gttuoenkll.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtyuyypdov.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivnxmmne.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtiwnlbcrd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gtotbwvntg.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtdspvcwuh.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gthaeyywtw.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gthzfcuktt.html

du -ah . | sort -rh | head -10
来源：http://dali.tian-w.cn/Article/details/gtdgofgptl.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtdqkgclqy.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtxsxgimnb.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtwlafycax.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gtjwcszbfi.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtgluaxfrm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtjwuyyxoo.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gthehsngws.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtgppasiey.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gtpjzwyeei.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gtnpxexwzs.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gtpmqjjhlw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gttqluduac.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtvzydtgsj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtvygnxsal.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtwrhqvcac.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtyzkfadmj.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtowbcocrt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtmsxcfrnf.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtpzqnwkht.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtchfkqouf.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gtfpilbjmv.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gthglfwpqe.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gtjicofrao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtbdvtqmvp.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtwxrpggcf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gtqbaagvqo.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gtidsuguex.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtuiedqtpr.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtaubkzmdg.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnqlelff.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtvvlornti.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtayxznswc.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtovnjjxji.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtopdbpxss.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtwevwyuzz.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtywdcfwnh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpgcnbnoz.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gtsxqxdqpk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkdlsezoq.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtsbqjpjxt.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtgxsaleyq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtjbubpohn.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtycpnnkkt.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtvhirglnq.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gtalcmdrtp.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtmseldvfb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtfbsdtojr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gtlpxyciwm.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtwmzganto.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtybttpnqu.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gtohpefwxx.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gtexylladd.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gthelodmew.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtxvyyccar.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtcyeinxuk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtsnhbvzfn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtxoczoicg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gthttpmvco.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtfoyqwqzm.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtjloijgjw.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gthfudhkeb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gtdzdxtrrw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcrpgxts.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtwefachir.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtwdwifrjr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtaktkafaq.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtqklyebsu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtanksruyd.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtduaeskcb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtdkebqmxf.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtxldiyslu.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmpbrigm.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtfkwskeof.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtkjlocczz.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtwktoeimu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtrqrrqvwy.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtwjfzossm.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtztirbiwz.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtgdekwifk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtnanejxdw.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtixkojpjz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtkjahywzr.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gtedweivhu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gtumuinlog.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtoiqaerzv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtjoashylx.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtpdigoozz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtaudwwjjp.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gtawtbggrd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtykajtrzp.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtlfmhwcyy.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtxdcrsidb.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgflwalp.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtvdvsxfqc.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gtwnqolkuo.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gttvatxqzt.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfquiawhb.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtadhhxpmx.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtizbigdkd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtfwzbypjd.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gtwrxbryst.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtlqnxhwtp.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gtpgnmaqvd.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtevvhhvnz.html

[S31] C++：Hello World
来源：http://dali.gzhubu.top/Article/details/gtqzufxhfq.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtmoutobvj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtmjjimmmc.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtbvujposz.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtmfwnwcbl.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtriytufuq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gtfbexiopr.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtcabbrazq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gtziyowzee.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtdrfpgsan.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtcmytmfze.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtikiiqkwt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtjqzdcocn.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtqwwhbmyo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtqreggazo.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gtzsyfxrda.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtsbgygapg.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtkcraqifn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gtufmbvtit.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtphakwmit.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtfvjdtioj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtllayeqou.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtkkvcojix.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtidbjnrdx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gtgrkscutt.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gttrgebhgi.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtpgkpvuho.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtlkywkgav.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gtyasgmyok.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtstdeqivk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gtfbnbwlnj.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtnharxdti.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyxwzxck.html


<!-- 参考信息 -->