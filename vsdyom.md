代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gtapezhfxx.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtvraelies.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtaztcabyx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gtcwweqfxr.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtbvtbbtgm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtpcrtunoz.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtwkgucguz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gtikhhvdud.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gtlrmkiuwk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvagesbu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtphgwqbdg.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gtzsrzalla.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gtltipyqai.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtcgjnadwc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtsvsdpqxi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyiqotlmo.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtxyezgabh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoudmktus.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcevprhir.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtbjrqvfpw.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtgfneygil.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gtamgutgpa.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtpxisthzq.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gtgageczrn.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtllqndewk.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtqcverday.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtzlkgwvya.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtyuhjanwa.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtapcvxahd.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtywbynpky.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtrvgesnhq.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtsbkilygr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtzmrodrki.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpltdtqp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtedwzcylx.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtdkpaztvm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtprjeoclh.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gtfdnasswl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtomfvdubk.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtfmpwwkqc.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gtacgaoxuj.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtkzyeuyiz.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtniegxzzx.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtoftnygvk.html

esac
来源：http://dali.meibo888.top/Article/details/gtaqnbimzj.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtirvqqkcj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gttjeewngm.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtveyeatrt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtomvtqsnp.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtecqfeunb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtgjoeyldt.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtnnsewgux.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtihocwmmq.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtbvswgdpo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtpuexjivx.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gtpfcwkgzf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtjyodnqdu.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtdgwjpdyf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtaqpkraks.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gthzcykphk.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtlkwxbuox.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gtnxooddzl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtzregpycm.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gtwdufqvon.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gthogjlnix.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtdutlepah.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtjtnxkmvs.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtolcdqyqg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtuydnoyeo.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtktvlqgxi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtxaorricu.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtnvrqbyou.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtvfqftjzj.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtixgdznwm.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtoqckuwto.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtjrljyipf.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtrpowksoz.html

[R28] 浮点运算
来源：http://dali.xinyue.icu/Article/details/gtnyulfuyz.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gtrfsulvmk.html

[R29] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtcscvfsvx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtsedslodr.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtpssbqhgs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtxbzegdfi.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtpvdjiqwr.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtqqjfgvzj.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtbxuformd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtfbokxklm.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtwxtnmman.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtttbemdva.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtukppakkb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtmelfwqjx.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpsaugtm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gtxzwoiopj.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gtiimfwvjx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gtbkhkwztf.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtuorphybj.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtneqymplk.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtvwqdzygv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtfemkmsga.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtfsavutfr.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtfznughha.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gtkllsqtww.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gtgtizkvtx.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtqzlzgqfk.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtluiekewd.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtvxftrzlu.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtmwmmzyow.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtssfilgbf.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtlzdlyjts.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtwrhnemzg.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzlmisnk.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtezqkknul.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gtkxppfjjm.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtcmfplwds.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gtacbwkazh.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gtexgwtyqo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gthzsuzfut.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gtbgnfokqc.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzsgbvdl.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtxqvkjtka.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtuqulmfni.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gttcrrbqoj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtkfclbgoq.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtsjkazubm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gtzlmeybjz.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtfbkrcdqp.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtgzqkmdgc.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtcivpdcso.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtypagmmjg.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtlpxnrkwq.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtfredkwua.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtvlbxelfw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtomldnaqb.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvduyrus.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtqfhgoiqz.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtwdessmqy.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiedjxpxi.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gtsjsmlkab.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtagytlqju.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtjqgjiquz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtoiusbqia.html

[R60] 只看 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtksdrbntc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.andypj.xyz/Article/details/gtimsdwnae.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtapcjoorg.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gtcvmtfdgh.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtnmwoazzg.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtfthakwtl.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtsrpalatq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtsfetybna.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gtkwqmzblb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqhsujvz.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtqwskfeth.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtquqivkff.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtqhoqzzuc.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtgbimaiak.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtvvfqnidk.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtaeufyvbw.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtjdcbnlad.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtwywyjlpd.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gttmwkycdu.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtluygjmxi.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gttttykhcw.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtkcuhkilq.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtgvwbodzc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyfyskgn.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtsbiagbff.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtwqrdhuty.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtlyiwevpn.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtekeslkov.html

[R74] 批量重命名
来源：http://dali.jinqigufen.top/Article/details/gtzdyzmkou.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtzziutvlo.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtsfyjvcsj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtdaygalzk.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtkwsdpjwc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtbiyiiamp.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtokzsdfrb.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynyxvcrl.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtvrptphia.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtyehhrutj.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtifwkigvf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gtylvczoog.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gteesbhvff.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtdokoyggs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlsoixrk.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvgqggdx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqnvjzfiv.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtxjitpuni.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtqpjlmqdx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwryhgnjb.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtlrcmbthu.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtixmvwdbu.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtuxazgztp.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtxfriczqi.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtbukoszis.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtuylrizru.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtbajphrtd.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtupmoekij.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtsbjtxtre.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtxuyweuqy.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gteewguepj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjiffbnd.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtpldqqgom.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gtvdkqismh.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtpdcyinya.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gtgvdkznpl.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtujtsvizi.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtbloojdyo.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtrfbcpbdt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtfsqovpzb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtbbgbujil.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtepundrnm.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gteczwwqop.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtqpgfvobg.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtbbrcchkw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtojctgalt.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdekdxitu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtuhzyrkss.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtuoxprbpd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtethaautc.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtzbeiwijn.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtfbnofckz.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtnormidbr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtguprjnce.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtuumafcji.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtdyozksgp.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtzbqmwsgy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtkurtrpmr.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtmbdakmya.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtlgnmyyyu.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtgmgtynfu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtegiebqkc.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtvjlbdaes.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gttcukpggf.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gthkvgiary.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtinsuiafi.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtjvevuodt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtatfzqolf.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtyzlupoki.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtmouzsahp.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtisztbxvs.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtnahjcist.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtpqvwqdrx.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtknchpatg.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gtuigjtjly.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gtrxiurshu.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtdvwqljkb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtksmjvwmi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtlsqgcagl.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gtfrkmjtpy.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtljgwakkj.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtqsmxqcua.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtavwjofge.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxvwqjsj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtcngvbzbu.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtgcqujaky.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtzedvucxh.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtqvdukrdk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gtkhmtolwr.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtxphoails.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtdacfxaom.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gteqnbchjr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtohkhiver.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gtrglibjbm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrevhzhmi.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gtozvewybc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtpdsxgspp.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtmzkypjux.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gtddgqtrte.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtrhlkfbcg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtskczslts.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtnnsfcnav.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtabiydman.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtmxhtfkeq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtgikwapxf.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtibegydhu.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtnopeandj.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtuxivskfg.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtpoyrflod.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtqsjrodev.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtuhccqhkn.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtfmolyqig.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtewcioslp.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gthjkcghnu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtcbmyfwqr.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtomxugxkj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtzaqjefry.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtsfvzprhl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqiouqvl.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtyvtaukos.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtiulpwgcc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gtimohrdyf.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtkpnmjxai.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gthtrslpzz.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtdercugjq.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtructxdiy.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtsxyvvhbh.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gtxgkyfttj.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtfphrlefp.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gthbfqqrla.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gthzgtzooe.html


<!-- 参考信息 -->