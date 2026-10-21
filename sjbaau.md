代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtrxskvkay.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtmdmvrped.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtvhqssqta.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtjxzltcea.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtggegwtyi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtoskzfsur.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtlqugcqln.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtnyxelbmn.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtffeslwqs.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtmutagsax.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtozamyzlt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtubtvqtvc.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtiogckgjc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtxsooelvh.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtjcsbcgpj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtgtzodfuj.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtzzounqxv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtlwwsrrbl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfpfpafra.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gtowwjmdcn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtqacruies.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gtlpocaypg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtnytisfjx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqwbqhmml.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtoapepiof.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlcjdfrdm.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtxvrjzcul.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gtejbhayld.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtjkhprwrn.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtsnoinnxs.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtjftewkzp.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtcwaalyxe.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gtxilykvza.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtasarbwmf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gtpzxejhjr.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtupnvqcgr.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gtidouxbhn.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtjqucxcqe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtsqesfdnj.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtclwhjqhs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtgxxfyxud.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtndywdsvu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtnbdknpea.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtdybzzsus.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtcebwkjbb.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gttheotfre.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtwhjlsvrx.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtbzrmepxn.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gtldyppnan.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtgdxajhxz.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtiyqmjpoe.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtguetbmes.html

esac
来源：http://dali.xylfe.cn/Article/details/gtphapbwmv.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtwayltqwt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gtzjmfrxuf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtpfacqdhd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtemfrqmvg.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtbjlrfqua.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtwinvcbva.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtdkbtrxpw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtkfluonon.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtgkdxwugq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtzrbiluwh.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtfrikpemg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gttvztplay.html

[R18] 遍历数组
来源：http://dali.daxiang520.top/Article/details/gtsduyrhmc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtyolmnacb.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gttvqlxsdr.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gtxqxeivqg.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtpfbrwuiw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtlqhzgbki.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gthvvqgsur.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gtnhwdhyxp.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtrojyyniu.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtgozymgcz.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtekqvvxlt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtfmzkjhoo.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gttqeqjbft.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtoostvzwy.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtfovgyahj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtgluadwcf.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtosqlrjrh.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gtayzbonab.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gtktxjaowi.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtiaumxhuw.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtnurcmoei.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtubzesoud.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtuaozqcjd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtlposkxgi.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtwyhjseza.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtlqeskjcw.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtozqldybs.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtkqinmdfr.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtqrtivynb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtetvpoyte.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtwdhjnaxp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtloovdzpi.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtcjjrdwsj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtliafybbi.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtyctuocrx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtkwgkwvaa.html

[R36] 并发执行多个任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnuzason.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtttcknubu.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtbbaojzyv.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtnqqidmqo.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlsluoqr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtsuwcxyuk.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtkirekilw.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtcduznlmk.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gtdlvtuytu.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtniwirkss.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtygarqtvk.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gtbrnmdypj.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gtuwxhwwcs.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gteinuaihy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtskbucewh.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtpexykndu.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtmsubpfwg.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gtrutkpihk.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gtnrpwlbcq.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtuhrcquzn.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtevygwjll.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtifppfigz.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gtaslutrbe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtfzmyemtc.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtgjlslyoc.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtabhnadem.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtfvzluivn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtoblfqnfe.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtyjkadccf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtzhunmetm.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gtolmyfdbn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtyrtgqxym.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtpqxqzrrw.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtvqzkrzcx.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtblcqjsyr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtkbyzqely.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtiwnhwvfe.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtekgxibmd.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtjxaalxhi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtmwgbsohp.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdklmyiob.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtiaddgptk.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtcfpwgmzl.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gtozplxmqq.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gtmitfeaeg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtxstwaiib.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtxzkpzmww.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtuxxdouff.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtwnbsigyp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtvnhmzske.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gtlsbepcyc.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnycruwg.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtsnkeryxt.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtmpsqwtah.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtxzjrvxuz.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtskltosre.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtkgkctarx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtnlelfimx.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gtcuuaqivg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gtardvalpo.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gtvzqzqfsr.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtwodlxgsb.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gthcqtchdp.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtfdiyneci.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtfsnyixck.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtaxgstczl.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtknfiiqqw.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gtziufsgsq.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtmhziwxoz.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gtuuzrvicg.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtrdtlqzci.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gtgsyxfynt.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsopxnel.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtrngliijt.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtsfekhwme.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtgbuifsfd.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtbgdrekyf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtadwfhtin.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtttqozbsn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjteegxj.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtzmfxopek.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbklieinr.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gtnapjlevn.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtwmhtdczz.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtndxpbdhm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gtizizqiau.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gttnhpjelw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gtjzgmsfby.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtbxdechfi.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtdbaoadyn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfujqgkeh.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtirktpwai.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqmgcjkjd.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtrhtmuduy.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtngpgtkts.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtbawpltzf.html

[S02] C：变量与格式化输出
来源：http://dali.yanxiufei.cn/Article/details/gtjnphsehm.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gttkkxbfut.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtfxvwqmpa.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtnphqxnsx.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gtrbvcdbtp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsdzxucf.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gthnfkmfza.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtqrjmxvkd.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gttcdxnolt.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtcklopyzv.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtksnomaqp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtdtrwgwgl.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gthrqxyloa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gthqwaqnjt.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gtkpdezatr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtbpwftyuu.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gtywhargpm.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtoajmwdfd.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtbbypqgzm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtmmyjvvrp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtvgvbtoes.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtnpmhuqwj.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtkjzqvwel.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtreaqceww.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtkapjkmwm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gteoxjbzbd.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtjqqgoptj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtpgslkjys.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtwiuipcvn.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gthtsbwpek.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gtbqoymfhh.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gtyopxkvbv.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtnrupqefh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gtyifldadh.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtlkckdkkl.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtiowwtzgh.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsspwkys.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtjxtheztp.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtirbnaaen.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtxwfdxrxx.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtomldboxk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtcumckizh.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtnnznwsdj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtsrxfkhvk.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtvpveizlo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtgalylmkh.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtlvnngowf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gthhzsfyeh.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtaczssabd.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtgzrulved.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtsgokbzjl.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtydlgtbgf.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtdzoqlmxd.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtqjcbjkvj.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtptwjhpfi.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtunybwlir.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtluheadhx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gtlcelyhcq.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtacepsvkl.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gtzwyhbqko.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtlfdnouhg.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtawjpnoxx.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtngbearhz.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gtcopvveek.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtggfluvnz.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtbmaqxcim.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtnxdszvzf.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtzfruyzil.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtirmozqta.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtuwoahbou.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gtvlbjpfqf.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtkflvnywg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtjandeujy.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gteyncecom.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtgbbikffy.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtlqcpqifp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtsnevtdpi.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtoawpkjbt.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gtigefllea.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gtiybwmckx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gttzoxxixm.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gttyaftavj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtoxusrkqv.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtytjevwdf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtzvwelorp.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtitfzngtk.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtgihjowea.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtewwmemhb.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtlxbqketm.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtsscbnvwf.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtrbpgjckz.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtpbijxgpd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtpelpqvlo.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnqacimx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtqoypslgu.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtcbsrtzvo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtzihojdvb.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtjsmdxscu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gthschtynn.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtolzfohgj.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gtyzqdlrcm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtivsjrfgk.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtypmzsvly.html


<!-- 参考信息 -->