代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2chxpanxt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gt2xjgclncu.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gt2amgyqdrp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gt2apkftcjq.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2xpglwcfn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gt2omdfcbmf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2kwttnpkk.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2cdllccwy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfysvwvv.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gt2mpuavfrx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gt2knlfzwgq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2iototsnq.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2ttxtzsby.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmazffyf.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gt2rywqqutu.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gt2trxxtigw.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gt2ooufaacu.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2nlnmwuea.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gt2sgqijzbz.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gt2pfeaskxl.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gt2hwcuqdsv.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2eigjvpzq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gt2zfbapchv.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gt2gdfagvda.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gt2vxjzjpcp.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2mrgfsbsu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2tvvbyuqn.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gt2iacdvccv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2lrxciqgd.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2hwxqpivq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2gjauikcq.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2mleeswir.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2eosjpiex.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gt2yomhjeyo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2ozzvkmsv.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gt2hcmjcxkk.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edjpcpmm.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2esjagint.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2slzbxffo.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gt2piwmmiuv.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gt2hkjawpsw.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gt2tvikujje.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gt2ftqmcpkp.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gt2laxjuuib.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2wbxxfzfz.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gt2vxsikvvs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gt2nvxqydso.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xbmfhcaz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gt2xkxxezrp.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2dnyvenfo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gt2vvpiirib.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhkfzehg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gt2xamszjxw.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gt2bwvfuoil.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gt2ojtdaxxm.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2ddpgczsr.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gt2opbnebve.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gt2bsjptofp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2kcbggdja.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmncfaaa.html

echo "${#s}"
来源：http://dali.tian-w.cn/Article/details/gt2emjplmkw.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2xesbcrat.html

echo "${s:0:5}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgioglda.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2ymokoyvi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gt2mexhcvco.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2chhirgba.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2qzizavvh.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2aymixtiw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gt2vgcvoiou.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2idksjkqw.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gt2zjdzascq.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gt2uqdnjvzz.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2pmmgusrn.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrjjfkui.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gt2ypzzywug.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2mlaobine.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gt2wesmlcjp.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gt2jedveout.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2ijljyghs.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gt2vwqruiug.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2veiqwzcr.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2gvuhirwb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2phkqdxkk.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gt2kasairxn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gt2vbgujrvl.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gt2xlyuhock.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2enfeamrc.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gt2iqqupell.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gt2knrcdezv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxwrebj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gt2cfcgxbze.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2mekyayqh.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2yhrdmped.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gt2ztiafmuj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gt2geftgffo.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gt2gntcrhud.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gt2jpanfwew.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gt2bdhgmnmc.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gt2ozlogrpc.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gt2lmdpabhm.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2vhgichtw.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gt2xkvsnldc.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2pdzxoefu.html

[R43] 按名字查找文件
来源：http://dali.yj202588.top/Article/details/gt2sftlkikz.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gt2fzkvlwug.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gt2qyhumrzx.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gt2iijvgile.html

[R45] 批量删除
来源：http://dali.zdqjudy.top/Article/details/gt2wynuhxti.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gt2fsztytab.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gt2dsdolmwj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gt2zeblyawo.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2mkcaphff.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2bhwtekhr.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivlonynw.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2ejlmfhof.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gt2xugsgrxc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gt2zilypvsq.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gt2xkkmcajb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2sseehumh.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gt2rrhsfhdi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gt2rbwopwgs.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gt2mnvuayws.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ieylcadg.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gt2uenddehg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2dkjvjdiy.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2haiothlt.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsmoqytt.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gt2vxedhaco.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gt2lzgicpkl.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xknfviyi.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avvpvsas.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2civnwibc.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gt2oefgojil.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gt2lqzqewvv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gt2pujyuzcu.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2uqxzyznb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cashguo.top/Article/details/gt2neqovaqu.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2fsxbqzkl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.andypj.xyz/Article/details/gt2qlvecvvo.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gt2hjwztege.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gt2nwtunnfw.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xpqiiwmj.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gt2hgkiayrj.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2ixlyfrtb.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drftsubv.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gt2lhvnrnjn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gt2xdowskyn.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gt2poqwpyzm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gt2nbvvncjs.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2despndcj.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gt2mbxycuhr.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmdyayjm.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2tjssmerg.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gt2qzltfzvv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhoraiam.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gt2dbmpfonp.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2unfwuiqy.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gt2vgeikdqv.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gt2jiaorkox.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2aowkpepa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gt2rnpzqreo.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gt2nzvzumft.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2oooqtwow.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rwngztfm.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2grkxycos.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gt2jqtyfzlj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2fdsjabsl.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2sljjgozp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qubgaynl.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2tcqkztpe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uadggeqb.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gt2vswmskwt.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2xaqorogp.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gt2znjrccmj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gt2bpqeyvqn.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gt2eyvamxda.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2zgjzdjqm.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2wsgddqap.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gt2bpcidlxr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edjdeutp.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gt2adkygzii.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2mrzjqkiq.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2fehawrir.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gt2odhinwkf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gt2vmjheruo.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2mnhkcgqv.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gt2difxakul.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijloflcp.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2wdhthegh.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gt2mapuvyyw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2nvdrqhlx.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gt2lyxgcewn.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gt2dzsankot.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2ebbgncxu.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gt2xuvcrjtd.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gt2kqtegyqp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gt2tvxoqimp.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gt2uqvszike.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gt2qbmzloat.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2omptojbi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gt2nagdaunc.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gt2jnqbjfqn.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gt2uwgfxgba.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2aaxkpwxk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2dvxvkdqq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2bjypxszi.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2mnkixrmn.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ukyskswa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbeexosd.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwpmjwmo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjjlxqb.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnkkyfme.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2milhsxer.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpmzexby.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gt2knzxmcrj.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2lshcexre.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gt2izomwais.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2hxjqrxrw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gt2vwjqoefy.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2sdqmvfox.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teybolqo.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gt2aotertyb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2qgqdpawe.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzbvynqt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2ntydfqts.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gt2cleddegy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gt2zzcgblcp.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2fxiumlvn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gt2pfqalzev.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gt2jodbqdnp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gt2gbwsmfht.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2hgqqgsbi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gt2ksoelzfe.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gt2nxhqtmiq.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gt2tzvzbfzk.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gt2ixypebch.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gt2pudoidcf.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2foqczpee.html

const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2clonksal.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2btdvzhds.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2hpbcxmia.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gt2yevgsgkv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gt2wesaesjx.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gt2danhnzxf.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnsqtwxt.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2pyrmxwby.html

#endif
来源：http://dali.hnqzz.top/Article/details/gt2nsxeuwye.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2lsqpovoo.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2muvxkvet.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gt2llnyhumo.html

[S32] C++：字符串
来源：http://dali.gogol.net.cn/Article/details/gt2vbpoxlku.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gt2huynffge.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2xdbarkak.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2okpiukun.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gt2ictzbhco.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gt2yfqsvhxf.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gt2oqdjaxmg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2usrziqlc.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gt2iebczfde.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2lnjkqsil.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gt2uatnvzxp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2utwokbtd.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gt2xqwoxaje.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2jucthbnc.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gt2oajnkmej.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2bpoixseq.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gt2rmqhwgbw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gt2auqjpfud.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gt2teuusaej.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2jruxcbky.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqzzmajo.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gt2ucrgcthf.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gt2tergfjrq.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gt2hpodhfpk.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gt2pljwvwna.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gaxexvwl.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gt2nlfrqjkp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gt2kqbkhaih.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gt2upddkzpn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2zbdygaqd.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2xnnjvjtk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tinwqczx.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2mmnemwks.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2sxcggqvj.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxudbnzr.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2merbhqul.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2pyztymob.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfuxhhcq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojpruwvc.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2rbgztzku.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gt2sgqmowhk.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gt2tqlfpkeu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmpujzn.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gt2lwyflaab.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gt2cfcvlspi.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fugkfvhr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gt2vbrjjiqz.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxxhgdzr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcehikri.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gt2jjdndjqa.html


<!-- 参考信息 -->