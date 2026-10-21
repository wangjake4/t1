代发 wailian999

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gthhlisnlb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtxmskpvjl.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtibndasyy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtdjccxvsx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtnnigiwre.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtihwdncpi.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtesbeanai.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtpvswajdh.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gtoxqixkts.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwsnlirkk.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtpngenfvi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtoglhfdot.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsweyfptc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtvlqhtcsd.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtqotbmrce.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gtphantorq.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtyyyhwdqg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gthlmglzxh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtidydefki.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtwyznwyla.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtuwjkrpzi.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtjcwtylmz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gtstfortho.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgvzngtxi.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtyjvovljo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuivhthnv.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtghqkaoeu.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtpkvnumfr.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtgpubreik.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gtngxenkpm.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtzzzmacub.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gthwwruxll.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtlquiytzs.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtqwbvasny.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtdkmxgain.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gthwpgcvuo.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtvpyufqgr.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtojumempg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gttvlndtxw.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gtwdbeywxv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtayftzfkd.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtwipwajuc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtrqyhcygo.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtwlwoyahq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gtctasytgf.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gtpebmookj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtceqhncuo.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtfihkdvzr.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtilvexjra.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gtzykmxsea.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gticeryamk.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gthlonqtef.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtklcjaong.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtdhqsmzxe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtghsdxpdl.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtkxmkbhta.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtspyqsroy.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtcvlfgwpa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtoyifdyna.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtmppxvjun.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gtmgbgthty.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtdmrigjbs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtqcwfgnfo.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtstpzbvdv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtymdhwuxl.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gtfkglzlhu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtuocklfmf.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtilcuqdxr.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtdpielkvw.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gtyuceafra.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtgkgzhtsi.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtsdgaivah.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtjtbqhvsf.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gthtratlse.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtcaspovxv.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtwbhyfoxt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtavupxlxb.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtxptgdcva.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtkrjjwpfk.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gtyjipptag.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gthvihqhua.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtogzwqdnw.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gtdaqgqpyz.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtissudsmx.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtabyeohvv.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtuipcbxnr.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtheqshvon.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtjwsmpfuk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtximmnhqh.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtjdclleml.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtpjjwehzt.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtguhzbton.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtgrsjttmx.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtdgnsrnjc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtlxgcjuci.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtqmhtobmu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtisjdxgic.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtenufaevq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtrpelzqav.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gthgpijnyn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gtvzkzcsja.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gthtpwuknw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnccwliq.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtqiuqhrjk.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gtpstucigo.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gtairtcgjx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtfwaqpnbq.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtnozidtzt.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtbcwazzra.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gtcqggfpwc.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtizkiwfwx.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtuyyaycjo.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtvcaeowla.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtzajahszn.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtrrxpwgys.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gttofjpkdg.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtreindzur.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gtttsiqulx.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gthbzqlxzt.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtlutbkhin.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gtgejmxtlk.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtfobqmzgm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtakljorzu.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtkvhnocka.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtgghoawfa.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtgogfvoda.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtkwkycumx.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gtvtwjdaat.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gtjjsfaxoc.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtjgnfvweq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtgsbmjyuc.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtcfmbcuil.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gtwbdjqcnd.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtfeunrjnc.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtabtatiek.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtjjaqxriy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gtoxschffu.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtcwbbcvle.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gtmsidhghl.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtqrcrzazl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gtsutogkfp.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtvcokzkci.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtpuyawaal.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gtncxdgdrn.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gtpnduaxhq.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtfzmvifay.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtfybjyxoh.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtoiirnvcb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtazaedviw.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtkzlmcguk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtzjrznfpk.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtkiysvzba.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gtxuuvgkbi.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtswcurwyk.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gtyadiadhu.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gtpvkwfwls.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gtfydsvjqh.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtsranlopd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtwxblyuag.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gtxadyuyjh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtwqwsbdlc.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtwuawxlsd.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gthglfduld.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtdubpsfhk.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtezwlyjeb.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtadqhngov.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtwopmfyar.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtzfrptibw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gtyczhbnkm.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtdnphkzju.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgttkhjw.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtqoycsqes.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gthxdgfouz.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtsohzsgpz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtslyjtzzl.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gtzxyyetsk.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtjcngnqtj.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtolfkmlut.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtsnywpavg.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gtbfznwkpf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gtpaoxcroz.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtjjolxyhj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtmdersejc.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gteepxhzvq.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtjledbhdw.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriisixje.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtcuznyqgp.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtbtfjyjnk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtolkoeuxo.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtgokhflyu.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtixmvefcb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxjbkejmw.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gtwarsiqdi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtiszslbny.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtnjbeyrpn.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtpjisvbsa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtdssidtes.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdkcmjwe.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gthxwwnxpm.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtulufeysq.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtfitsxprp.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtwtgsfplo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtacnegekj.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtcqtznpav.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gthddzabup.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gtcduuuskh.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtblnhwwqi.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmsjhgtp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtfcjgsfjb.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gtdeaeckzo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtyypsjfcx.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtpwpfjmmp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtwidxkgjd.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtkexdevbl.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtfguqtprd.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtixwonhkw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtgpdswqln.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtdammdwvl.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtipkdrsax.html

[S12] C：写文件
来源：http://dali.cucudq.cn/Article/details/gthnrvokcd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyjwszzc.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtknicsral.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtdtslobae.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtgflqlbgr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtpwocwhci.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtwkcipgfv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtonowusid.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gtnvcdkpky.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtyyfukrgs.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtvyljpgsy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtweqsqfvf.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtvheoikfb.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtopwhayoh.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtwyxmxqjz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtmwuhokxj.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtegkhzisv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtvfaddvra.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtcocxwqqs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtyvgxbjgc.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtcaomyfjg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtzvyhrzqv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtopkrkkjo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtcteffdqd.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtlxjtquzi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtiwahyrwf.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gterituqvt.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gthufwngsr.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gthpgsblis.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtgpwrequm.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtxjsabnxa.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gttjzqavxd.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtheqxgtkn.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahjkbfdr.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtktkzwbme.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtcdirwsmw.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtjvuvanel.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwquynnh.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gttxikszeh.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtwalpmxcl.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtvqmnpzlu.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtnaqbxjpx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtefphpjnn.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtulyvyxyx.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gturagcukg.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtjbyhddvo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtgfxbfndl.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtdsifuyfq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gttmftqsla.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtdctezdvs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtuomwretl.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtgdrecmvm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtreqaimxe.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtyydrstje.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gttocwktow.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gtkxyrswzv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtzivfhpnd.html

[S39] C++：自定义比较器排序
来源：http://dali.yueranfly.top/Article/details/gtcnwzhpxs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gtigntywgc.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtnpuahwrv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtgcnovaet.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtdjgkwqmr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtxakpwiwf.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtywbgzwas.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtajswiywa.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gtfawrrysq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtodvmdieg.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtyhgwuzhx.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtqbssjjci.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtmqssrztt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtbhmoukyp.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtashljhwh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqnsozlqd.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtsaztoeeh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtwecbiwuh.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtbfgfmsdd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtoozxaylw.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtvrlzsauh.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtzxxscumj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtrhhcfuez.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtaugtgrzx.html


<!-- 参考信息 -->